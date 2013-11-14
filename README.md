#Implementation and Evaluation of Pub/Sub overlays for P2P Social Networks

Pub/Sub systems are gaining popularity due to their use in a variety of
novel attractive applications, such as privacy-preserving decentralized
social networks. In pub/sub systems, subscribers express their interests
by subscribing and later get notifications when the publishers publish
events matching their subscriptions. In topic-based pub/sub,
subscriptions are expressed as discrete topics while publication events
are associated with these topics. Topic-based pub/sub systems are deemed
instrumental for delivering notifications in a decentralized social
networks scenario, which motivates the need to investigate P2P pub/sub
solutions.

A number of P2P topic-based pub/sub systems have been proposed in the
past decade. However, several challenges remain to be solved. To this
end we recently proposed a P2P topic-based pub/sub system coined
PolderCast [1], which builds and maintains a pub/sub overlay used for
efficient dissemination of publication events. In the PolderCast paper
we presented a preliminary mini-survey of state-of-the-art topic-based
pub/sub systems, which clearly illustrated different characteristics of
these systems and their shortcomings. However, there is a need for even
deeper analytical or empirical evaluation and comparison of these
systems. Such study and comparison would be a great contribution to the
research community.

The goal of this master thesis is to perform an evaluation of several
topic-based Pub/Sub systems mentioned in Section 3 of the PolderCast
paper [1]. For some of the systems, there already exists an available
implementation. For the other systems, there is a need to implement them
in Java using a P2P simulator such as PeerSim [2] (the choice of
programming language can be discussed). Ideally, we should be able to
deploy the implementations on a real network including the widely used
PlanetLab [3] testbed. The evaluation of these systems should be
conducted w.r.t several metrics using workloads from Facebook and
Twitter. The thesis will provide hands-on experience with
state-of-the-art pub/sub and P2P protocols and technologies. Thanks to
the PlanetLab deployment, the student will also gain experience in
designing and developing large-scale deployment of protocols over the
wide Internet. Such an experience is likely to give an edge in future IT
career, whether in academia or industry.


References: [1] Vinay Setty, Maarten van Steen, Roman Vitenberg, and
Spyros Voulgaris, "PolderCast: Fast, Robus, and Scalable Architecture
for P2P Topic-based Pub/Sub", To appear in Middleware 2012 [pdf] [2] A.
    Montresor and M. Jelasity. “PeerSim: A scalable P2P simulator.” In
    P2P Computing, 2009. [url] [3] PlanetLab:
    https://www.planet-lab.org/

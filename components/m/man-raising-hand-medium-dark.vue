<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQ8054g)" class="ew0_z4b2p"/><path fill="url(#is0rcAc)" class="ew0_z4b2p"/><path fill="url(#iTlaJte)" class="ew0_z4b2p"/><path fill="url(#iKRqggb)" class="ew0_z4b2p"/><path fill="url(#iRYGcsB)" class="ew0_z4b2p"/><path fill="url(#if0EDhb)" class="ew0_z4b2p"/><path fill="url(#ipNDrty)" class="ew0_z4b2p"/><path fill="url(#inMl11f)" class="ew0_z4b2p"/><path fill="url(#iVE5cub)" class="ew0_z4b2p"/><path fill="url(#i9ZVhLx)" class="ew0_z4b2p"/><path fill="url(#iQilOme)" class="ew0_z4b2p"/><g filter="url(#ijXjy0t)"><path stroke="url(#iTaw6ed)" class="fszodmbjn"/></g><g filter="url(#iQ2hmHe)"><path stroke="url(#iuxeYae)" class="c-juupheu"/></g><g filter="url(#io2SOve)"><path stroke="url(#ibdAsZd)" class="cipz1dbii"/></g><g filter="url(#iLAcGqe)"><path stroke="url(#ijKgLRn)" class="s2ov-34xr"/></g><g filter="url(#i6NPLjb)"><path stroke="url(#iiTgN0d)" class="e0ih67b7f"/></g><g filter="url(#ifLIY4b)"><path stroke="url(#ihBP9if)" class="nl57x8r1p"/></g><g filter="url(#ijfBhEe)"><path stroke="url(#ibs1oie)" class="yt6p73q0x"/></g><g filter="url(#ixB81Cc)"><path stroke="url(#iZ9KiDd)" class="q2lc8ihwl"/></g><g filter="url(#iCoiSVb)"><path stroke="url(#ivqeOFe)" class="b1d33ubvm"/></g><g filter="url(#iEYLdfd)"><path stroke="url(#ihwWzNc)" class="cgo1hobpm"/></g><path fill="url(#iRfl7Hi)" class="rxlkd8fet"/><path fill="url(#iQZc29d)" class="rxlkd8fet"/><path fill="url(#iIeNOje)" class="rxlkd8fet"/><path fill="url(#i9nqOUX)" class="m9o6ctbkx"/><path fill="url(#ifToh7d)" class="m9o6ctbkx"/><path fill="url(#iEhAl4c)" class="m9o6ctbkx"/><path fill="url(#iyKrJwb)" class="u-x33kb1i"/><path fill="url(#i0eobCe)" class="u-x33kb1i"/><path fill="url(#iecN90d)" class="u-x33kb1i"/><path fill="url(#it7XIxb)" class="u-x33kb1i"/><path fill="url(#iY8WYxc)" class="u-x33kb1i"/><path fill="url(#iuYKoPb)" class="u-x33kb1i"/><path fill="url(#iFggTAw)" class="bjhm05mmf"/><g filter="url(#iiuINbc)"><path stroke="url(#ittRUHc)" class="wx81jjtbd"/></g><g filter="url(#i6bKfkc)"><circle fill="url(#iKDQ9qc)" class="w6p-26byj"/></g><g filter="url(#iaTuSGY)"><circle fill="url(#i2yv98g)" class="xsidu6b_l"/></g><g filter="url(#isMhtHD)"><circle fill="url(#i3Lr7Rb)" class="du-02hbml"/><circle fill="url(#iLv3qsb)" class="du-02hbml"/></g><g filter="url(#ixdIgoe)"><circle class="z6r0x6b3t"/><circle fill="url(#iApJmzd)" class="m2x97tn3c"/><circle fill="url(#iyFESUb)" class="m2x97tn3c"/></g><g filter="url(#iukodJb)"><path fill="url(#iiDHhjb)" class="kdgxvk09u"/><path fill="url(#iB9qZDb)" class="kdgxvk09u"/><path fill="url(#ivp39eB)" class="kdgxvk09u"/></g><path fill="url(#i8RbWfd)" class="u6cw494tt"/><path fill="url(#iXbypEd)" class="u6cw494tt"/><path fill="url(#i2cCfKc)" class="u6cw494tt"/><path fill="url(#i8k5AbS)" class="u6cw494tt"/><g filter="url(#imWGbWb)"><path fill="url(#i0su4Gd)" class="yvhs37gkx"/></g><g filter="url(#itoA9Zb)"><path class="q2aa-g_8k"/><path fill="url(#iWdIdcc)" class="jr7kh_6oz"/><path fill="url(#iN1wx6d)" class="jr7kh_6oz"/><path fill="url(#ieYJpKd)" class="jr7kh_6oz"/><path fill="url(#iTatDXd)" class="jr7kh_6oz"/></g><g filter="url(#iivPhae)"><path class="p3ja0bbld"/></g><g filter="url(#iaowplp)"><path class="saj6ze3pz"/><path fill="url(#i2g9nLe)" class="rmmr44bcc"/><path fill="url(#igOtUXb)" class="rmmr44bcc"/><path fill="url(#iFLBTwd)" class="rmmr44bcc"/><path fill="url(#iFGTO3c)" class="rmmr44bcc"/></g><path fill="url(#itl4hAd)" class="rmmr44bcc"/><path stroke="url(#idJxxOb)" class="wchhtibux"/><g filter="url(#iUb6Zfb)"><path class="k7ge6_5fe"/><path fill="url(#ionlOtd)" class="bpzz_nhiz"/></g><g filter="url(#iQF6bZr)"><path class="x3lh-5bwc"/><path fill="url(#i8eCA9d)" class="efvdhqbkp"/></g><path class="hqyotm_tq"/><path fill="url(#iJkVXOe)" class="rxv5yv7ix"/><path class="kje75b9wa"/><g filter="url(#i9Jm0AN)"><path class="btqu_0-kn"/><path fill="url(#ii7f73b)" class="chvjh80zm"/></g><g filter="url(#iqmhkmd)"><path fill="url(#i12vEZb)" class="lu9o5ebrk"/></g><path class="husc23i3j"/><path fill="url(#iCOFFrd)" class="krxvn8b5v"/><path class="wlppcfj6w"/><g filter="url(#i5IXSzb)"><path fill="url(#itlE40b)" class="s94q9pbxp"/></g><g filter="url(#iqVCeKd)"><ellipse transform="rotate(-27.914 16.388 13.264)" class="euqaf7lnq"/><ellipse fill="url(#i8WKNBy)" transform="rotate(-27.914 16.388 13.264)" class="d2er6jldj"/></g><g filter="url(#iL2xBRm)"><path stroke="url(#ibNhdqc)" class="sd735qbdp"/></g><g filter="url(#iQmimpe)"><path stroke="url(#iiC5nsc)" class="qy6hngfsc"/></g><g filter="url(#i2plBIc)"><path stroke="url(#ixhzdZd)" class="d-d07jfhq"/></g><defs><radialGradient id="iQ8054g" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.186 11.54)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="o-iirh5hj"/><stop offset="1" class="b4grpcbtk"/></radialGradient><radialGradient id="is0rcAc" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 3.013 7.221)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="nui0_5bvt"/><stop offset="1" class="aijb2v7yw"/></radialGradient><radialGradient id="iKRqggb" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.91 4.728)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="iRYGcsB" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.558 3.563)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="if0EDhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.528 2.798)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="ipNDrty" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 10.027 3.159)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="inMl11f" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 8.1 2.13)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="iVE5cub" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.874 3.9)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="i9ZVhLx" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 4.285 3.947)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="iQilOme" cx="0" cy="0" r="1" gradientTransform="matrix(-.88951 .77545 -.60682 -.69608 12.067 6.798)" gradientUnits="userSpaceOnUse"><stop class="bq0xhibbj"/><stop offset="1" class="khbnhvbup"/></radialGradient><radialGradient id="iQZc29d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 7.44 12.322)" gradientUnits="userSpaceOnUse"><stop class="zen3jbcth"/><stop offset="1" class="e873ol6-u"/></radialGradient><radialGradient id="ifToh7d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68288 2.79847 -2.9931 -9.28678 26.41 27.07)" gradientUnits="userSpaceOnUse"><stop class="ul7rmpbso"/><stop offset="1" class="ezu_a_bod"/></radialGradient><radialGradient id="iEhAl4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.19204 2.98189 0 11.2 30.436)" gradientUnits="userSpaceOnUse"><stop class="iqmfu1bfz"/><stop offset="1" class="b_ji9tgfr"/></radialGradient><radialGradient id="i0eobCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.29 12.87)" gradientUnits="userSpaceOnUse"><stop class="v74r7idhd"/><stop offset="1" class="hk_d6vbsx"/></radialGradient><radialGradient id="iecN90d" cx="0" cy="0" r="1" gradientTransform="rotate(-167.876 10.083 9.18)scale(10.3399 4.20474)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="dz4ncrwcz"/><stop offset="1" class="ou0802bre"/></radialGradient><radialGradient id="it7XIxb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.7286 12.06 15.781)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="pzn0rnkkd"/><stop offset="1" class="zpuae6b8t"/></radialGradient><radialGradient id="iFggTAw" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3731 -4.14332 0 19.323 20.773)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="rcw9-ibyp"/><stop offset="1" class="m6wa8nbco"/></radialGradient><radialGradient id="iKDQ9qc" cx="0" cy="0" r="1" gradientTransform="matrix(2.09017 0 0 3.65781 11.67 14.19)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iLv3qsb" cx="0" cy="0" r="1" gradientTransform="matrix(.98466 -.71698 .81834 1.12387 25.431 13.874)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iApJmzd" cx="0" cy="0" r="1" gradientTransform="matrix(.9782 -1.79914 1.05305 .57254 24.94 15.168)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iyFESUb" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -4.759 37.478)scale(.43454 .56019)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iB9qZDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55682 1.91609 0 22.107 12.675)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="ivp39eB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.63666 2.03533 0 16.678 12.835)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i2cCfKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.74013 -13.2217 0 18.953 12.077)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="expufxtqh"/><stop offset="1" class="cpvcnac5k"/></radialGradient><radialGradient id="iWdIdcc" cx="0" cy="0" r="1" gradientTransform="matrix(.95026 -3.52154 1.3059 .35239 24.488 9.299)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iN1wx6d" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -67.17 248.962)scale(4.57489 2.45989)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ieYJpKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.00001 -3.09746 0 19.313 3.945)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iTatDXd" cx="0" cy="0" r="1" gradientTransform="matrix(3.66129 -2.68308 4.20351 5.73603 11.632 12.066)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iFGTO3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23452 -.75346 0 19.703 16.103)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ionlOtd" cx="0" cy="0" r="1" gradientTransform="matrix(.1241 -.71853 2.12574 .36714 22.222 11.707)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i8eCA9d" cx="0" cy="0" r="1" gradientTransform="matrix(.12411 -.71853 2.12585 .3672 16.09 11.708)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iJkVXOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96611 -1.53671 0 21.908 13.377)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ii7f73b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.119 1.44)scale(.45046 .62018)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCOFFrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96616 -1.53679 0 16.711 13.377)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8WKNBy" cx="0" cy="0" r="1" gradientTransform="matrix(-.00921 -.58835 .70722 -.01107 16.37 13.639)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iTlaJte" x1="6.668" x2="6.668" y1="12.201" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="yt_0wt3yl"/><stop offset="1" class="eujvqlb2y"/></linearGradient><linearGradient id="iTaw6ed" x1="5.158" x2="5.168" y1="4.895" y2="6.897" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iuxeYae" x1="6.579" x2="6.606" y1="4.466" y2="6.829" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ibdAsZd" x1="8.338" x2="8.341" y1="5.066" y2="6.513" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ijKgLRn" x1="3.924" x2="4.344" y1="5.008" y2="7.615" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iiTgN0d" x1="5.069" x2="5.281" y1="4.134" y2="7.258" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="ihBP9if" x1="7.218" x2="8.32" y1="3.378" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="ibs1oie" x1="8.173" x2="8.489" y1="4.327" y2="7.759" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iZ9KiDd" x1="5.219" x2="4.127" y1="6.875" y2="6.806" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="ivqeOFe" x1="6.491" x2="5.927" y1="6.703" y2="6.562" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="ihwWzNc" x1="7.992" x2="7.189" y1="6.516" y2="6.303" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iRfl7Hi" x1="4.509" x2="8.884" y1="12.432" y2="12.432" gradientUnits="userSpaceOnUse"><stop class="w8p93gb0x"/><stop offset=".743" class="m--3robwq"/></linearGradient><linearGradient id="iIeNOje" x1="6.779" x2="6.779" y1="11.846" y2="12.104" gradientUnits="userSpaceOnUse"><stop class="qp7m7zbwo"/><stop offset="1" class="va6027bik"/></linearGradient><linearGradient id="i9nqOUX" x1="21.507" x2="5.77" y1="30.71" y2="12.869" gradientUnits="userSpaceOnUse"><stop class="cgidz9b8x"/><stop offset=".401" class="qxg6rvb4w"/></linearGradient><linearGradient id="iyKrJwb" x1="9.776" x2="10.507" y1="26.537" y2="21.71" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrwls_btk"/><stop offset="1" class="tilf7ac3p"/></linearGradient><linearGradient id="iY8WYxc" x1="14.045" x2="13.306" y1="24.561" y2="23.166" gradientUnits="userSpaceOnUse"><stop offset=".35" class="lign7ubxp"/><stop offset=".794" class="iu5n-nb1z"/></linearGradient><linearGradient id="iuYKoPb" x1="7.305" x2="7.305" y1="12.869" y2="13.909" gradientUnits="userSpaceOnUse"><stop class="nwxnfd6vs"/><stop offset="1" class="uwkg4cb-r"/></linearGradient><linearGradient id="ittRUHc" x1="7.322" x2="13.072" y1="14.577" y2="22.858" gradientUnits="userSpaceOnUse"><stop class="rtxxuvbkk"/><stop offset="1" class="cm0qez-we"/></linearGradient><linearGradient id="i2yv98g" x1="13.658" x2="12.895" y1="14.522" y2="14.522" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="i3Lr7Rb" x1="26.283" x2="25.308" y1="12.89" y2="15.911" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iiDHhjb" x1="24.12" x2="15.024" y1="14.654" y2="16.009" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="i8RbWfd" x1="12.886" x2="15.127" y1="17.865" y2="17.785" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iXbypEd" x1="25.107" x2="23.849" y1="16.867" y2="16.747" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="i8k5AbS" x1="19.347" x2="19.347" y1="20.72" y2="21.97" gradientUnits="userSpaceOnUse"><stop offset=".533" class="m8c2yi15h"/><stop offset="1" class="vbfhreb6b"/></linearGradient><linearGradient id="i0su4Gd" x1="18.68" x2="28.38" y1="11.099" y2="7.626" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="i2g9nLe" x1="18.284" x2="19.401" y1="15.439" y2="15.439" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="igOtUXb" x1="20.431" x2="19.209" y1="15.823" y2="15.806" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iFLBTwd" x1="19.545" x2="19.545" y1="16.707" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="itl4hAd" x1="19.463" x2="19.463" y1="16.757" y2="16.558" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="idJxxOb" x1="18.078" x2="18.596" y1="18.631" y2="17.812" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i12vEZb" x1="22.834" x2="22.461" y1="13.442" y2="13.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itlE40b" x1="17.597" x2="17.223" y1="13.442" y2="13.672" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibNhdqc" x1="22.853" x2="22.353" y1="10.893" y2="9.871" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iiC5nsc" x1="16.535" x2="15.118" y1="10.741" y2="10.147" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ixhzdZd" x1="13.76" x2="13.76" y1="8.342" y2="10.911" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="ijXjy0t" width=".423" height="2.22" x="4.765" y="4.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".05"/></filter><filter id="iQ2hmHe" width=".345" height="2.572" x="6.32" y="4.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".05"/></filter><filter id="io2SOve" width=".509" height="1.681" x="7.797" y="4.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".05"/></filter><filter id="iLAcGqe" width="1.556" height="3.487" x="3.631" y="4.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".2"/></filter><filter id="i6NPLjb" width="1.2" height="3.889" x="5.316" y="3.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".2"/></filter><filter id="ifLIY4b" width="1.488" height="4.773" x="6.864" y="2.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".2"/></filter><filter id="ijfBhEe" width="2.002" height="4.299" x="8.267" y="3.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".2"/></filter><filter id="ixB81Cc" width="1.412" height="1.358" x="3.921" y="6.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".1"/></filter><filter id="iCoiSVb" width="1.118" height=".999" x="5.57" y="6.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".1"/></filter><filter id="iEYLdfd" width="1.312" height="1.023" x="6.835" y="6.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".1"/></filter><filter id="iiuINbc" width="9.217" height="11.911" x="5.665" y="12.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".75"/></filter><filter id="i6bKfkc" width="4.177" height="3.977" x="11.669" y="12.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="iaTuSGY" width="3.37" height="3.37" x="11.973" y="12.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".25"/></filter><filter id="isMhtHD" width="4.227" height="4.227" x="23" y="11.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="ixdIgoe" width="3.37" height="3.37" x="23.304" y="12.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".25"/></filter><filter id="iukodJb" width="12.356" height="14.576" x="13.169" y="7.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="imWGbWb" width="9.057" height="7.653" x="17.515" y="5.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation="1"/></filter><filter id="itoA9Zb" width="15.009" height="10.08" x="11.808" y="3.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="iivPhae" width="3.596" height="4.693" x="17.23" y="12.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".375"/></filter><filter id="iaowplp" width="2.735" height="3.693" x="17.945" y="13.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".125"/></filter><filter id="iUb6Zfb" width="3.501" height="2.154" x="20.721" y="9.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="iQF6bZr" width="3.501" height="2.154" x="14.589" y="9.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3867"/></filter><filter id="i9Jm0AN" width=".899" height=".791" x="21.053" y="12.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".05"/></filter><filter id="iqmhkmd" width=".985" height="1.011" x="22.072" y="12.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".1"/></filter><filter id="i5IXSzb" width="1.098" height="1.162" x="16.782" y="12.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".1"/></filter><filter id="iqVCeKd" width="1.049" height=".801" x="15.864" y="12.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".05"/></filter><filter id="iL2xBRm" width="3.703" height="2.013" x="20.541" y="9.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".25"/></filter><filter id="iQmimpe" width="3.795" height="2.081" x="14.324" y="10.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".25"/></filter><filter id="i2plBIc" width="1.058" height="2.56" x="13.231" y="8.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3867" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-raising-hand-medium-dark" /></template>
<style>
.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.aijb2v7yw {
  stop-color: var(--svg-color--6a413b, #6A413B);
  stop-opacity: 0;
}

.b_ji9tgfr {
  stop-color: var(--svg-color--4496db, #4496DB);
  stop-opacity: 0;
}

.b1d33ubvm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.388 6.714c-.13.164-.332.3-.518.4");
}

.b4grpcbtk {
  stop-color: var(--svg-color--7a544a, #7A544A);
}

.bjhm05mmf {
  d: path("M19.323 23.975c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.bpzz_nhiz {
  d: path("m23.743 10.95l-.001-.001l-.003-.002l-.005-.004l-.014-.012a2 2 0 0 0-.185-.128a3 3 0 0 0-.5-.25a3.4 3.4 0 0 0-1.778-.19a.636.636 0 0 0 .199 1.257c.474-.075.853.012 1.112.115a1.8 1.8 0 0 1 .367.197a.636.636 0 0 0 .808-.982");
}

.bq0xhibbj {
  stop-color: var(--svg-color--866a60, #866A60);
}

.btqu_0-kn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.832 13.034c.076.101-.082.225-.262.36s-.314.229-.39.127c-.075-.1.01-.292.19-.427c.18-.134.387-.161.462-.06");
}

.c-juupheu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.528 4.462l-.07 2.297");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cgidz9b8x {
  stop-color: var(--svg-color--38a2f1, #38A2F1);
}

.cgo1hobpm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.847 6.522c-.13.165-.501.36-.712.423");
}

.chvjh80zm {
  d: path("M21.832 13.034c.076.101-.082.225-.262.36s-.314.229-.39.127c-.075-.1.01-.292.19-.427c.18-.134.387-.161.462-.06");
}

.cipz1dbii {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M8.168 5.063L7.934 6.47");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm0qez-we {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
  stop-opacity: 0;
}

.cpvcnac5k {
  stop-color: var(--svg-color--7d4371, #7D4371);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.ct57ro4xv {
  stop-color: var(--svg-color--95766f, #95766F);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-d07jfhq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.914 8.46v1.068c-.01.177-.084.573-.308.74");
}

.d2er6jldj {
  cx: 16.388px;
  cy: 13.264px;
  rx: 0.464px;
  ry: 0.235px;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.du-02hbml {
  cx: 24.989px;
  cy: 14.19px;
  r: 1.988px;
}

.dz4ncrwcz {
  stop-color: var(--svg-color--09538b, #09538B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0ih67b7f {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.916 3.575v3.089");
}

.e873ol6-u {
  stop-color: var(--svg-color--3983b7, #3983B7);
  stop-opacity: 0;
}

.efvdhqbkp {
  d: path("m14.818 10.95l.002-.002l.006-.004l.014-.012a2 2 0 0 1 .184-.128c.119-.074.287-.167.5-.25a3.4 3.4 0 0 1 1.778-.19a.636.636 0 0 1-.198 1.257a2.1 2.1 0 0 0-1.112.115a1.8 1.8 0 0 0-.367.197a.636.636 0 0 1-.809-.981");
}

.eujvqlb2y {
  stop-color: var(--svg-color--724130, #724130);
  stop-opacity: 0;
}

.euqaf7lnq {
  cx: 16.388px;
  cy: 13.264px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.464px;
  ry: 0.235px;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ew0_z4b2p {
  d: path("M3.606 8.905c-.125-1.922-.281-2.959-.328-3.641c-.035-.512.023-1.067.71-1.192c.599-.074.884.452.907.66c-.002-.2 0-.679 0-.804c0-.211.008-.977.86-.977c.6 0 .816.588.8.864c.01-.102.023-.414.035-.707c.019-.434.252-.99.946-.977c.597.04.793.613.765.977l-.117 1.867c.024-.188.103-.665.278-1.34s.701-.72.957-.684c.326.047.88.361.648 1.274c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.413 1.001-.788c.36-.375.887-.382 1.184-.16c.34.293.522.967.12 1.37c-.463.425-2.13 2.405-2.958 3.394c-.229.292-.997.875-2.234.875c-2.203-.093-2.942-1.676-3.047-3.296");
}

.expufxtqh {
  stop-color: var(--svg-color--7d4371, #7D4371);
  stop-opacity: 0;
}

.ezu_a_bod {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
  stop-opacity: 0;
}

.fj2hmbbmv {
  stop-color: var(--svg-color--714131, #714131);
  stop-opacity: 0;
}

.fszodmbjn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.903 4.892l.148 1.945");
}

.ft5dv1b6b {
  fill: none;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.hk_d6vbsx {
  stop-color: var(--svg-color--3394d1, #3394D1);
  stop-opacity: 0;
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hqyotm_tq {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.157 12.486c.778 0 1.435.536 1.613 1.26a.326.326 0 0 1-.319.406h-2.656a.274.274 0 0 1-.27-.323a1.665 1.665 0 0 1 1.632-1.343");
}

.husc23i3j {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.463 12.486c-.778 0-1.435.536-1.614 1.26a.327.327 0 0 0 .319.406h2.657a.273.273 0 0 0 .27-.323a1.67 1.67 0 0 0-1.633-1.343");
}

.i3e9u7gak {
  stop-color: var(--svg-color--997a6f, #997A6F);
  stop-opacity: 0;
}

.iqmfu1bfz {
  stop-color: var(--svg-color--4496db, #4496DB);
}

.iu5n-nb1z {
  stop-color: var(--svg-color--2877cd, #2877CD);
  stop-opacity: 0;
}

.jr7kh_6oz {
  d: path("m25.052 6.474l.511.254c.895.445 1.406 1.462 1.214 2.541l-.703 3.621c-.062.374-.31.626-.68.635h-.022s.064-1.08.128-1.715c.051-.516-.039-.673-.512-1.143c-.255-.254-.447-.635-.447-1.016V8.634c0-.317-.255-.572-.51-.635c-.768-.19-2.365-.508-4.665-.508s-3.897.317-4.664.508a.62.62 0 0 0-.51.635v1.017c0 .38-.129.762-.448 1.016l-.192.19c-.255.191-.383.572-.383.89c.064.699.128 1.715.128 1.715q-.03 0-.059-.002a.754.754 0 0 1-.708-.633l-.703-3.621c-.127-1.016.384-2.033 1.278-2.478l.511-.254c.32-.19.64-.444.959-.698l1.15-1.207c.702-.636 1.725-.826 2.619-.382a3.5 3.5 0 0 0 1.98 0c.959-.317 2.045-.063 2.812.636l.958.953c.255.317.575.508.958.698");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jx7ffbcje {
  stop-color: var(--svg-color--997a6f, #997A6F);
}

.k7ge6_5fe {
  fill: var(--svg-color--352827, #352827);
  d: path("m23.743 10.95l-.001-.001l-.003-.002l-.005-.004l-.014-.012a2 2 0 0 0-.185-.128a3 3 0 0 0-.5-.25a3.4 3.4 0 0 0-1.778-.19a.636.636 0 0 0 .199 1.257c.474-.075.853.012 1.112.115a1.8 1.8 0 0 1 .367.197a.636.636 0 0 0 .808-.982");
}

.kdgxvk09u {
  d: path("m13.239 13.46l.058.002s-.064-1.016-.128-1.715c0-.318.128-.699.383-.89l.192-.19c.32-.254.447-.635.447-1.017V8.635A.62.62 0 0 1 14.702 8c.767-.19 2.364-.508 4.664-.508s3.898.317 4.664.508c.256.063.511.317.511.635V9.65c0 .382.192.763.447 1.017c.599.419.561.65.512 1.143c-.064.636-.128 1.715-.128 1.715h.021l-.316 4.715c-.191 2.108-1.848 3.577-3.824 3.577h-3.824c-2.04 0-3.632-1.47-3.824-3.577z");
}

.khbnhvbup {
  stop-color: var(--svg-color--866a60, #866A60);
  stop-opacity: 0;
}

.kje75b9wa {
  fill: var(--svg-color--000, #000);
  d: path("M21.302 13.872c0-.338.27-.608.608-.608a.606.606 0 0 1 .542.888h-1.078a.55.55 0 0 1-.072-.28");
}

.krxvn8b5v {
  d: path("M16.709 12.81a1.063 1.063 0 0 0-1.024 1.342h2.053q.037-.135.038-.28a1.07 1.07 0 0 0-1.067-1.063");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7n7uk6bh {
  stop-color: var(--svg-color--331c1a, #331C1A);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lign7ubxp {
  stop-color: var(--svg-color--2790d8, #2790D8);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lu9o5ebrk {
  d: path("M22.857 13.732a1 1 0 0 0-.275-.55l-.31.339l.14.272z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m--3robwq {
  stop-color: var(--svg-color--1b6b9f, #1B6B9F);
}

.m2x97tn3c {
  cx: 24.989px;
  cy: 14.19px;
  r: 1.185px;
}

.m6wa8nbco {
  stop-color: var(--svg-color--6e5056, #6E5056);
}

.m8c2yi15h {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
  stop-opacity: 0;
}

.m9o6ctbkx {
  d: path("M20.288 20.87h.97c2.49 0 7.472 3.5 7.472 9H10.797v-3.5a.67.67 0 0 0-.414-.626L7.31 24.37c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.424-1.015.932-1.015h4.114c.518 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.978 1.5z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nl57x8r1p {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.752 2.664l-.289 3.944");
}

.nrwls_btk {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
}

.nui0_5bvt {
  stop-color: var(--svg-color--67383d, #67383D);
}

.nwxnfd6vs {
  stop-color: var(--svg-color--408dc5, #408DC5);
}

.o-iirh5hj {
  stop-color: var(--svg-color--815854, #815854);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou0802bre {
  stop-color: var(--svg-color--1473af, #1473AF);
  stop-opacity: 0;
}

.p3ja0bbld {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m18.985 14.044l-.977 2.025c-.121.416.17.832.581.832h.878c.412 0 .703-.422.582-.832l-.594-2.025c-.127-.448-.337-.448-.47 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pzn0rnkkd {
  stop-color: var(--svg-color--3473ab, #3473AB);
}

.q2aa-g_8k {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m25.052 6.474l.511.254c.895.445 1.406 1.462 1.214 2.541l-.703 3.621c-.062.374-.31.626-.68.635h-.022s.064-1.08.128-1.715c.051-.516-.039-.673-.512-1.143c-.255-.254-.447-.635-.447-1.016V8.634c0-.317-.255-.572-.51-.635c-.768-.19-2.365-.508-4.665-.508s-3.897.317-4.664.508a.62.62 0 0 0-.51.635v1.017c0 .38-.129.762-.448 1.016l-.192.19c-.255.191-.383.572-.383.89c.064.699.128 1.715.128 1.715q-.03 0-.059-.002a.754.754 0 0 1-.708-.633l-.703-3.621c-.127-1.016.384-2.033 1.278-2.478l.511-.254c.32-.19.64-.444.959-.698l1.15-1.207c.702-.636 1.725-.826 2.619-.382a3.5 3.5 0 0 0 1.98 0c.959-.317 2.045-.063 2.812.636l.958.953c.255.317.575.508.958.698");
}

.q2lc8ihwl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.221 7.68c.11-.063.617-.38.813-.758");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q7h19xvvk {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qp7m7zbwo {
  stop-color: var(--svg-color--186a98, #186A98);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxg6rvb4w {
  stop-color: var(--svg-color--268fd7, #268FD7);
}

.qy6hngfsc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.074 11.396c.39-.345 1.24-.708 2.295-.54");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rcw9-ibyp {
  stop-color: var(--svg-color--673a48, #673A48);
}

.rmmr44bcc {
  d: path("m18.858 13.85l-.633 2.024c-.13.417.18.833.62.833h.936c.44 0 .75-.423.62-.833l-.633-2.024c-.135-.448-.768-.448-.91 0");
}

.rtxxuvbkk {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
}

.rxlkd8fet {
  d: path("M4.673 12.046c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.rxv5yv7ix {
  d: path("M21.91 12.81a1.063 1.063 0 0 1 1.024 1.342h-2.053a1.067 1.067 0 0 1 1.029-1.343");
}

.s2ov-34xr {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.229 4.53l.36 2.634");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s6abn5boy {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
}

.s94q9pbxp {
  d: path("M17.68 13.747c0-.343-.28-.572-.355-.641l-.343.332l.21.43z");
}

.saj6ze3pz {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m18.858 13.85l-.633 2.024c-.13.417.18.833.62.833h.936c.44 0 .75-.423.62-.833l-.633-2.024c-.135-.448-.768-.448-.91 0");
}

.sd735qbdp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.29 10.778c.513-.09 1.512-.064 2.203.474");
}

.tilf7ac3p {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tvgnczn8r {
  stop-color: var(--svg-color--714131, #714131);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u-x33kb1i {
  d: path("m18.681 20.979l-7.874 5.245a.66.66 0 0 0-.4-.48L7.323 24.37c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.u6cw494tt {
  d: path("M13.17 11.747c0-.318.127-.699.383-.89l.191-.19c.32-.254.447-.635.447-1.017V8.635A.62.62 0 0 1 14.702 8c.767-.19 2.364-.508 4.664-.508s3.898.317 4.664.508c.256.063.511.317.511.635V9.65c0 .382.192.763.447 1.017c.599.419.561.65.512 1.143c-.064.636-.128 1.715-.128 1.715h.021l-.316 4.715c-.191 2.108-1.848 3.577-3.824 3.577h-3.824c-2.04 0-3.632-1.47-3.824-3.577c-.166-2.163-.238-4.333-.436-6.493");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ul7rmpbso {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
}

.uwkg4cb-r {
  stop-color: var(--svg-color--408dc5, #408DC5);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v74r7idhd {
  stop-color: var(--svg-color--3394d1, #3394D1);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.va6027bik {
  stop-color: var(--svg-color--186a98, #186A98);
  stop-opacity: 0;
}

.vbfhreb6b {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w6p-26byj {
  cx: 13.658px;
  cy: 14.19px;
  r: 1.988px;
}

.w8p93gb0x {
  stop-color: var(--svg-color--3688bf, #3688BF);
}

.wchhtibux {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.686 17.482a.23.23 0 0 0-.277.048a.21.21 0 0 0-.023.274a2.3 2.3 0 0 0 1.927 1.029c.809 0 1.52-.412 1.927-1.03a.216.216 0 0 0-.024-.276a.23.23 0 0 0-.276-.045a3.5 3.5 0 0 1-1.627.386c-.597 0-1.157-.14-1.627-.386Z");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wlppcfj6w {
  fill: var(--svg-color--000, #000);
  d: path("M17.318 13.872a.606.606 0 0 0-.61-.608a.606.606 0 0 0-.54.888h1.077a.6.6 0 0 0 .073-.28");
}

.wug9f7p2x {
  stop-color: var(--svg-color--95766f, #95766F);
}

.wx81jjtbd {
  d: path("M7.666 13.797v5.171a2 2 0 0 0 1.38 1.902l4.182 1.363");
}

.x3lh-5bwc {
  fill: var(--svg-color--352827, #352827);
  d: path("m14.818 10.95l.002-.002l.006-.004l.014-.012a2 2 0 0 1 .184-.128c.119-.074.287-.167.5-.25a3.4 3.4 0 0 1 1.778-.19a.636.636 0 0 1-.198 1.257a2.1 2.1 0 0 0-1.112.115a1.8 1.8 0 0 0-.367.197a.636.636 0 0 1-.809-.981");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xsidu6b_l {
  cx: 13.658px;
  cy: 14.19px;
  r: 1.185px;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yt_0wt3yl {
  stop-color: var(--svg-color--724130, #724130);
}

.yt6p73q0x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.674 3.71l-.812 3.407");
}

.yvhs37gkx {
  d: path("m24.034 7.49l-3.666 1.223a1.247 1.247 0 0 0 .56 2.42l3.645-.489z");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z0iyhs38d {
  stop-color: var(--svg-color--331c1a, #331C1A);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z6r0x6b3t {
  cx: 24.989px;
  cy: 14.19px;
  r: 1.185px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.zen3jbcth {
  stop-color: var(--svg-color--3983b7, #3983B7);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zpuae6b8t {
  stop-color: var(--svg-color--127cc2, #127CC2);
  stop-opacity: 0;
}

</style>

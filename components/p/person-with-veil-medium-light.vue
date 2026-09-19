<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irU30zs)"><path fill="url(#islCJXb)" class="eyq-j4rfj"/><path fill="url(#ioIWxld)" class="eyq-j4rfj"/><path fill="url(#iEv1sxf)" class="eyq-j4rfj"/></g><g filter="url(#ixIq4Ro)"><path fill="url(#ivbEkQN)" class="jfws982cr"/></g><path fill="url(#iVTY5Sb)" class="b59_i1b1o"/><path fill="url(#iA1j6ff)" class="b59_i1b1o"/><path fill="url(#iKuXPIb)" class="b59_i1b1o"/><path fill="url(#i5iuZHc)" class="b59_i1b1o"/><g filter="url(#i7Z44le)"><path class="fa0nsvbse"/></g><g filter="url(#i0YUL6G)"><path class="zsj5_9a3c"/></g><g filter="url(#iTWzbnc)"><path fill="url(#iXC7Lmd)" class="fv5c-3h7r"/><path fill="url(#iJt1yMe)" class="fv5c-3h7r"/><path fill="url(#iFRXisd)" class="fv5c-3h7r"/></g><g filter="url(#iC2xcrc)"><path fill="url(#ivNQXye)" class="ujg3-bcoe"/><path fill="url(#ifVGqfd)" class="ujg3-bcoe"/><path fill="url(#iYt3myd)" class="ujg3-bcoe"/></g><g filter="url(#i60t0Wc)"><path fill="url(#iVCGB1b)" class="vtlqp6_0b"/><path fill="url(#iJikIil)" class="vtlqp6_0b"/><path fill="url(#iGtFpZJ)" class="vtlqp6_0b"/><path fill="url(#iX69SPd)" class="vtlqp6_0b"/><path fill="url(#ihTRWfb)" class="vtlqp6_0b"/></g><path fill="url(#i3gw0le)" class="jt0rkibcj"/><path fill="url(#iIOh4ud)" class="jt0rkibcj"/><g filter="url(#ixlruke)"><path class="iwey-wb_a"/></g><g filter="url(#iex1Krj)"><path fill="url(#iTyFUGe)" class="r4tpvlruj"/><path fill="url(#iekJ1xd)" class="r4tpvlruj"/></g><g filter="url(#iUNmiKe)"><path fill="url(#iJ9tQcQ)" class="y_-nyz7qb"/><path fill="url(#ihiLRfd)" class="y_-nyz7qb"/></g><circle fill="url(#iHVMpMg)" class="vl91zwoht"/><circle fill="url(#i3U4Ukc)" class="vl91zwoht"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#indWxHb)" class="uuvm0cbel"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><path fill="url(#iGaC8Ub)" class="cf6_ffx9f"/><g filter="url(#iAcm29c)"><path class="xy2hs8s1u"/><path fill="url(#irFI0gb)" class="ct7mdhn7n"/><path fill="url(#iqY51Dc)" class="ct7mdhn7n"/><path fill="url(#ipNad4d)" class="ct7mdhn7n"/><path fill="url(#iUDmEOu)" class="ct7mdhn7n"/><path fill="url(#iQBxcQo)" class="ct7mdhn7n"/></g><path fill="url(#i4LXZSc)" class="gob_x5bhm"/><g filter="url(#iXTlHWd)"><path class="afbwhdcra"/><path fill="url(#in4gUjb)" class="o29dz2isc"/><path fill="url(#iVLocse)" class="o29dz2isc"/></g><g filter="url(#ixpsC1c)"><path class="a00kit5sj"/><path fill="url(#iPtVjEc)" class="q4l6o8wsh"/><path fill="url(#irdANWc)" class="q4l6o8wsh"/><path fill="url(#i3ONp1q)" class="q4l6o8wsh"/><path fill="url(#iZUiyFb)" class="q4l6o8wsh"/><path fill="url(#imxLKpc)" class="q4l6o8wsh"/></g><g filter="url(#i5H7WoR)"><path fill="url(#iraSsMe)" clip-rule="evenodd" class="wjlbdbb9g"/></g><g filter="url(#iDTBVHe)"><path class="edcynnb_d"/></g><g filter="url(#ii9HsHd)"><path fill="url(#iGgANae)" class="g5ilm9bus"/><path fill="url(#iILYo4b)" class="g5ilm9bus"/></g><g filter="url(#ij2jnIe)"><path stroke="url(#iXVKMPb)" class="mhejshymi"/></g><g filter="url(#iqPw6dJ)"><path stroke="url(#i343mgd)" class="y1diaublm"/></g><g filter="url(#ixedule)"><path stroke="url(#i6Fz0Td)" class="f26dbtbnd"/></g><g filter="url(#iLJ9x9R)"><path stroke="url(#icablxe)" class="w-m7nbbyp"/></g><path fill="url(#iPI1yje)" class="hlri6acty"/><path fill="url(#ioJDuCy)" class="b0k142a-q"/><path fill="url(#iQm6hvc)" class="b0k142a-q"/><path fill="url(#iqUieNH)" class="b0k142a-q"/><path fill="url(#iQm6hvc)" class="b0k142a-q"/><g filter="url(#i2D61Tc)"><path fill="url(#ing35Wd)" class="whr7lob7j"/></g><path fill="url(#iK5CXbb)" class="whr7lob7j"/><path fill="url(#iWFX8Nb)" class="whr7lob7j"/><path fill="url(#iNrTd7c)" class="whr7lob7j"/><path fill="url(#i78Ej1d)" class="whr7lob7j"/><path fill="url(#izMqOWc)" class="whr7lob7j"/><path fill="url(#imeiC8c)" class="whr7lob7j"/><path fill="url(#iZzbhlc)" class="whr7lob7j"/><path fill="url(#i5AuVhb)" class="whr7lob7j"/><g filter="url(#iTzdFXQ)"><path class="d966hwb4t"/></g><g filter="url(#iRnxHAc)"><path class="xnc1jsmbn"/><path fill="url(#i7nArjb)" class="jk83w1bwk"/><path fill="url(#ivfMcEb)" class="jk83w1bwk"/><path fill="url(#ippBirc)" class="jk83w1bwk"/></g><g filter="url(#iRBqlYd)"><path fill="url(#iMGNtTd)" class="uj62tebaw"/></g><g filter="url(#iT5asvb)"><path stroke="url(#iCLYxXd)" class="r5hnjw5if"/></g><path fill="url(#iahOwdd)" class="tbzx16bsb"/><g filter="url(#iYktCvb)"><path fill="url(#iZbKaVb)" class="izl0i66yg"/><path fill="url(#ipUtype)" class="izl0i66yg"/><path fill="url(#ieBiMvd)" class="izl0i66yg"/><path fill="url(#i2CzAte)" class="izl0i66yg"/><path fill="url(#iZOreZd)" class="izl0i66yg"/></g><g filter="url(#izwLuxb)"><path class="d82o6ccus"/></g><g filter="url(#iCmScOb)"><path class="igjos7bbi"/></g><g filter="url(#iv1wOae)"><path fill="url(#iq2tn6n)" class="dgmzqac2j"/><path fill="url(#iGu8Ptb)" class="dgmzqac2j"/></g><g filter="url(#ijCEWMc)"><path fill="url(#ijJLxwe)" class="u41-5rfbj"/><path fill="url(#i476nwd)" class="u41-5rfbj"/><path fill="url(#iSq6KTb)" class="u41-5rfbj"/><path fill="url(#iA0g3Jl)" class="u41-5rfbj"/><path fill="url(#ikSwIuc)" class="u41-5rfbj"/><path fill="url(#iBPzUMc)" class="u41-5rfbj"/></g><path class="s-t2v602m"/><path fill="url(#iz41Q0c)" class="xnxn7_5tz"/><path class="g6kbzgqhl"/><g filter="url(#i7HjOyO)"><path class="nsv25rq8i"/><path fill="url(#i4l4m9d)" class="r4jv9c8lc"/></g><g filter="url(#i6IoZ0b)"><path fill="url(#id4LBuc)" class="vzqcr0bpx"/></g><path class="d6k-wuuzd"/><path fill="url(#iUOobue)" class="kdhx9ccqp"/><path class="epkshozyc"/><g filter="url(#iBVJ6Cd)"><path fill="url(#i9DkaJL)" class="ljkpo-b0t"/></g><g filter="url(#iiaWBSH)"><ellipse transform="rotate(-27.914 13.554 9.902)" class="m619t0bjq"/><ellipse fill="url(#iquCPlb)" transform="rotate(-27.914 13.554 9.902)" class="kntkvs5su"/></g><path fill="url(#ij7OIOb)" class="ezur8_b6t"/><path fill="url(#iy6t1he)" class="ezur8_b6t"/><path fill="url(#iDV7Akf)" class="ezur8_b6t"/><path fill="url(#iDlFOcW)" class="q2r8kkkcb"/><path fill="url(#iLernnb)" class="q2r8kkkcb"/><g filter="url(#i7iaxCe)"><path class="zsvxa8b6p"/></g><g filter="url(#i0B9Bpe)"><path class="c-klx7bqf"/></g><g filter="url(#ih1aa7c)"><path class="h2i6rhwoc"/></g><g filter="url(#iSO7Iub)"><path class="zgweqebwb"/></g><g filter="url(#if8nXtv)"><path fill="url(#i7ArLZb)" clip-rule="evenodd" class="jzk7dab5r"/><path fill="url(#i5ziYRQ)" clip-rule="evenodd" class="jzk7dab5r"/></g><defs><radialGradient id="ioIWxld" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.83 7.015)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iEv1sxf" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.621)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iVTY5Sb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.153 15.728)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iKuXPIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.996)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i5iuZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.153)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iJt1yMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.79)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iFRXisd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.639 14.624)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ifVGqfd" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.293)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iYt3myd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.855)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iVCGB1b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.574)" gradientUnits="userSpaceOnUse"><stop class="rytnnmv8a"/><stop offset="1" class="b3fwc4m_l"/></radialGradient><radialGradient id="iJikIil" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.623)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="v0p7hcb9x"/><stop offset="1" class="licq-dbtd"/></radialGradient><radialGradient id="iGtFpZJ" cx="0" cy="0" r="1" gradientTransform="matrix(-3.10937 .98438 -.41833 -1.3214 16.117 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="fotkl_b9q"/><stop offset="1" class="ia04nc2ae"/></radialGradient><radialGradient id="iX69SPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.797)" gradientUnits="userSpaceOnUse"><stop class="qe7efdbrr"/><stop offset="1" class="ox8o7cb9c"/></radialGradient><radialGradient id="ihTRWfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.69)" gradientUnits="userSpaceOnUse"><stop class="ko0wcdkuo"/><stop offset="1" class="qqn01fflj"/></radialGradient><radialGradient id="i3gw0le" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.716 35.88)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iekJ1xd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.162 4.905)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ihiLRfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.292)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iHVMpMg" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.317 11.795)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i3U4Ukc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.422 14.59)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="indWxHb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.353 12.65)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iGaC8Ub" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.359 19.36)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="irFI0gb" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.28 20.215)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iqY51Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 22.996)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ipNad4d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.17 9.217)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iUDmEOu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.277 24.793)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iQBxcQo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.573)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="i4LXZSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.793)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="in4gUjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.7)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iVLocse" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.713)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iPtVjEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.278)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="irdANWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.965)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iraSsMe" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.311 16.628)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGgANae" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.839)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iILYo4b" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.226)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iPI1yje" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.466 11.688)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ioJDuCy" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.46 11.971)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iQm6hvc" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.203 12.423)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iqUieNH" cx="0" cy="0" r="1" gradientTransform="matrix(1.12304 3.55025 -1.61375 .51047 10.459 11.972)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="ing35Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.29158 0 0 -7.59176 18.815 10.914)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="fu5-5cbow"/></radialGradient><radialGradient id="iWFX8Nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4687 -10.3256 0 16.445 5.054)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="dlg0oqats"/><stop offset=".982" class="z67zbhbom"/></radialGradient><radialGradient id="iNrTd7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.454 9.794)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="i78Ej1d" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.465 -1.703)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="izMqOWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.126 11.299)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="imeiC8c" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.154 7.913)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iZzbhlc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.853 14.986)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i5AuVhb" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.965 5.533)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iCLYxXd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.56 -5.597)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="x9zya81jn"/><stop offset="1" class="d02js3bty"/></radialGradient><radialGradient id="iahOwdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.007 14.453)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ipUtype" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.777 9.332)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ieBiMvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.868 9.332)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i2CzAte" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.338 -.325)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iZOreZd" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.102 1.463)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iq2tn6n" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.876 2.875)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iGu8Ptb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.241 -5.762)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="ijJLxwe" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.628 4.066)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="i476nwd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.065 -1.752)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iSq6KTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.516 8.37)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iA0g3Jl" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.8 3.949)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="ikSwIuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.46 3.824)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iBPzUMc" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.826 7.348)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iz41Q0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.189 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4l4m9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.96 10.081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUOobue" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.825 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iquCPlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.539 10.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iy6t1he" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.625 10.012)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iDV7Akf" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.985 10.556)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iLernnb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.933 4.924)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="i5ziYRQ" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.67 8.583)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="irU30zs" width="21.944" height="26.818" x="4.962" y="3.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="ixIq4Ro" width="12.631" height="14.916" x="9.484" y="8.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/><feGaussianBlur result="effect2_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="i7Z44le" width="5.874" height="5.537" x="6.993" y="23.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".5"/></filter><filter id="i0YUL6G" width="4.98" height="4.054" x="18.51" y="24.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".5"/></filter><filter id="iTWzbnc" width="2.973" height="2.006" x="21.47" y="23.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="iC2xcrc" width="3.281" height="2" x="20.468" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="i60t0Wc" width="13.965" height="11.381" x="9.149" y="12.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.560784 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="ixlruke" width="10.996" height="6.432" x="11.932" y="21.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".5"/></filter><filter id="iex1Krj" width="2.973" height="2.006" x="7.658" y="23.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="iUNmiKe" width="3.266" height="2" x="8.366" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="iAcm29c" width="6.218" height="6.789" x="8.343" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3418" result="effect2_innerShadow_4002_3418"/></filter><filter id="iXTlHWd" width="6.218" height="6.639" x="17.574" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3418" result="effect2_innerShadow_4002_3418"/></filter><filter id="ixpsC1c" width="6.702" height="6.417" x="12.683" y="20.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="i5H7WoR" width="6.703" height="6.517" x="12.633" y="20.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".15"/></filter><filter id="iDTBVHe" width="3.2" height="3.2" x="14.271" y="22.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".25"/></filter><filter id="ii9HsHd" width="2.35" height="2.35" x="14.893" y="23.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="ij2jnIe" width="1.458" height="2.505" x="15.848" y="20.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="iqPw6dJ" width="1.723" height="1.924" x="16.94" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="ixedule" width="1.368" height="2.217" x="18.104" y="22.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="iLJ9x9R" width="3.55" height="1.942" x="15.171" y="17.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".25"/></filter><filter id="i2D61Tc" width="10.97" height="12.542" x="10.944" y="4.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3418" result="effect2_innerShadow_4002_3418"/></filter><filter id="iTzdFXQ" width="3.754" height="4.824" x="13.861" y="9.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".5"/></filter><filter id="iRnxHAc" width="2.077" height="3.1" x="14.969" y="9.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="iRBqlYd" width="2.077" height="3.1" x="14.969" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="iT5asvb" width="3.718" height="1.573" x="14.148" y="13.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="iYktCvb" width="12.873" height="8.356" x="9.571" y="1.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3418" result="effect2_innerShadow_4002_3418"/></filter><filter id="izwLuxb" width="2.339" height="1.19" x="17.596" y="7.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="iCmScOb" width="2.339" height="1.176" x="12.34" y="7.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><filter id="iv1wOae" width="6.584" height="5.992" x="9.926" y="2.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="ijCEWMc" width="6.362" height="5.736" x="15.848" y="3.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="i7HjOyO" width=".787" height=".696" x="17.455" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="i6IoZ0b" width=".891" height=".913" x="18.295" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".1"/></filter><filter id="iBVJ6Cd" width=".986" height="1.04" x="13.852" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".1"/></filter><filter id="iiaWBSH" width=".913" height=".704" x="13.097" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".05"/></filter><filter id="i7iaxCe" width="1.329" height="2.379" x="9.974" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="i0B9Bpe" width="1.447" height="2.403" x="20.719" y="9.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="ih1aa7c" width="2.405" height="1.16" x="12.259" y="7.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="iSO7Iub" width="2.405" height="1.16" x="17.538" y="7.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3418" stdDeviation=".125"/></filter><filter id="if8nXtv" width="15.448" height="4.54" x="8.283" y="2.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3418"/></filter><linearGradient id="islCJXb" x1="26.906" x2="11.7" y1="11.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="ivbEkQN" x1="20.7" x2="10.387" y1="17.402" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iA1j6ff" x1="14.887" x2="14.887" y1="30.871" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iXC7Lmd" x1="23.649" x2="21.867" y1="25.793" y2="24.383" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ivNQXye" x1="22.95" x2="21.169" y1="27.377" y2="25.683" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iIOh4ud" x1="12.653" x2="13.255" y1="29.262" y2="28.918" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iTyFUGe" x1="7.856" x2="9.361" y1="24.277" y2="26.097" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iJ9tQcQ" x1="9.062" x2="10.843" y1="27.377" y2="25.692" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i3ONp1q" x1="14.919" x2="16.7" y1="27.141" y2="22.871" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iZUiyFb" x1="13.356" x2="16.981" y1="22.903" y2="23.59" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="imxLKpc" x1="17.231" x2="16.325" y1="26.903" y2="25.153" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iXVKMPb" x1="16.477" x2="16.477" y1="20.824" y2="22.832" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i343mgd" x1="17.286" x2="18.153" y1="24.879" y2="26.082" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="i6Fz0Td" x1="18.728" x2="18.728" y1="22.411" y2="24.027" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="icablxe" x1="16.132" x2="20.117" y1="19.022" y2="17.851" gradientUnits="userSpaceOnUse"><stop class="cylb5xhsz"/><stop offset="1" class="zcstuupfv"/></linearGradient><linearGradient id="iK5CXbb" x1="21.164" x2="16.811" y1="12.6" y2="12.6" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i7nArjb" x1="16.946" x2="16.007" y1="11.866" y2="12.007" gradientUnits="userSpaceOnUse"><stop offset=".095" class="h76ykhble"/><stop offset="1" class="w-gq83bca"/></linearGradient><linearGradient id="ivfMcEb" x1="14.934" x2="16.009" y1="11.587" y2="11.646" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ippBirc" x1="16.007" x2="16.007" y1="12.141" y2="12.993" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iMGNtTd" x1="16.007" x2="16.007" y1="9.7" y2="10.892" gradientUnits="userSpaceOnUse"><stop offset=".218" class="xd7cd0__n"/><stop offset="1" class="ag2a5bbnb"/></linearGradient><linearGradient id="iZbKaVb" x1="21.371" x2="11.247" y1="5.251" y2="5.251" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="id4LBuc" x1="18.967" x2="18.653" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9DkaJL" x1="14.569" x2="14.255" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ij7OIOb" x1="22.443" x2="21.236" y1="10.079" y2="12.255" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iDlFOcW" x1="10.157" x2="11.616" y1="10.782" y2="10.655" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="i7ArLZb" x1="20.481" x2="8.544" y1="3.652" y2="7.339" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-veil-medium-light" /></template>
<style>
.a00kit5sj {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.afbwhdcra {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.ag2a5bbnb {
  stop-color: var(--svg-color--dfa58b, #DFA58B);
  stop-opacity: 0;
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b0k142a-q {
  d: path("M11.146 12.163a1.64 1.64 0 0 1-.905-.309v.932c0 .893.532 1.688 1.341 2.019a4.1 4.1 0 0 1-.346-1.18z");
}

.b3fwc4m_l {
  stop-color: var(--svg-color--da9f7c, #DA9F7C);
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b59_i1b1o {
  d: path("M27 29.934v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.559 5 23.734 5 28.934v1z");
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.c-klx7bqf {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.969 11.604q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cf6_ffx9f {
  d: path("m11.186 26.303l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.136.085 3.001z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct7mdhn7n {
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cylb5xhsz {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
}

.d02js3bty {
  stop-color: var(--svg-color--d8a192, #D8A192);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d6k-wuuzd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.616 9.248c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.d82o6ccus {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.74 7.934a1.85 1.85 0 0 0-.687-.412c-.305-.096-.686-.121-1.213-.057a.277.277 0 0 0 .067.55c.482-.058.776-.027.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.417");
}

.d966hwb4t {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.576 10.578l-.692 1.655c-.101.378.142.757.487.757h.735c.344 0 .588-.384.486-.757l-.496-1.838c-.107-.407-.408-.224-.52.183");
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dgmzqac2j {
  d: path("m16.24 5.298l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.485z");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dlg0oqats {
  stop-color: var(--svg-color--cc8985, #CC8985);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.edcynnb_d {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.358a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.epkshozyc {
  fill: var(--svg-color--000, #000);
  d: path("M14.334 10.413a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.454.747h.904a.5.5 0 0 0 .061-.236");
}

.eyq-j4rfj {
  d: path("M5.062 16.434c0-8.813 4.89-13.22 10.922-13.22s10.922 4.22 10.922 13.22v13.5H5.062z");
}

.ezur8_b6t {
  d: path("M20.929 12.255q.101-1.595.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f26dbtbnd {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.574c.307.136.83.616.461 1.453");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.fa0nsvbse {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.145c.879-.05 1.658.637 1.72 1.534l.009.116c.31.044.61.175.862.398l.107.113a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.15.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fotkl_b9q {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
}

.ft5dv1b6b {
  fill: none;
}

.fu5-5cbow {
  stop-color: var(--svg-color--cd9480, #CD9480);
}

.fv5c-3h7r {
  d: path("M21.48 25.295c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5ilm9bus {
  d: path("M15.993 25.226a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.g6kbzgqhl {
  fill: var(--svg-color--000, #000);
  d: path("M17.68 10.413a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .454.747h-.904a.46.46 0 0 1-.06-.236");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gob_x5bhm {
  d: path("m20.799 26.303l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.136-.085 3.001z");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h2i6rhwoc {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.634 8.105c.257-.185.897-.51 1.655-.382");
}

.h76ykhble {
  stop-color: var(--svg-color--f8c4a6, #F8C4A6);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hlri6acty {
  d: path("M20.868 12.163c.335-.01.65-.124.905-.309v.932c0 .893-.532 1.688-1.341 2.019q.256-.546.346-1.18z");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.ia04nc2ae {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
  stop-opacity: 0;
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.igjos7bbi {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.596 7.825a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.438z");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iwey-wb_a {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.41c.096.053.144.218.081.348l-.668 1.39c-.181.388-.526.925-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.324-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.437a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.175a.042.042 0 0 0 .055-.042l-.025-.402c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.665.81-1.062v.467c0 .028.028.048.055.039l.458-.156a1 1 0 0 1 .223-.058l.036-.084l1.043.853c.063-.129.19-.198.295-.152c.711.328.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.695 2.682-1.36");
}

.izl0i66yg {
  d: path("M20.862 4.27a2.33 2.33 0 0 1 1.268 1.052a2.37 2.37 0 0 1-.107 2.526a1.56 1.56 0 0 0-.27.875V9.91a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.35 2.35 0 0 1 1.299-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.581.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jfws982cr {
  d: path("M9.984 15.856c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.435H9.984z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jk83w1bwk {
  d: path("m15.625 10.199l-.532 1.838c-.108.378.152.757.52.757h.787c.37 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jt0rkibcj {
  d: path("m13.196 29.933l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.jzk7dab5r {
  fill-rule: evenodd;
  d: path("M15.972 4.364c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 0 1-1.16-1.027c.88-.997 3.165-2.903 7.494-2.903c4.41 0 6.608 1.915 7.54 2.877A.775.775 0 1 1 22.4 6.77c-.735-.758-2.556-2.406-6.428-2.406");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kdhx9ccqp {
  d: path("M13.823 9.52a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kntkvs5su {
  cx: 13.554px;
  cy: 9.902px;
  rx: 0.39px;
  ry: 0.197px;
}

.ko0wcdkuo {
  stop-color: var(--svg-color--db977c, #DB977C);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.licq-dbtd {
  stop-color: var(--svg-color--d6927c, #D6927C);
  stop-opacity: 0;
}

.ljkpo-b0t {
  d: path("M14.639 10.308c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m619t0bjq {
  cx: 13.554px;
  cy: 9.902px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhejshymi {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.027c.324 0 .758.377.758.86v.945");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nsv25rq8i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.125 9.709c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.o29dz2isc {
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ox8o7cb9c {
  stop-color: var(--svg-color--db9f70, #DB9F70);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q2r8kkkcb {
  d: path("M10.953 9.055a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q4l6o8wsh {
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qe7efdbrr {
  stop-color: var(--svg-color--db9f70, #DB9F70);
}

.qqn01fflj {
  stop-color: var(--svg-color--db977c, #DB977C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r4jv9c8lc {
  d: path("M18.125 9.709c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.r4tpvlruj {
  d: path("M10.52 25.295c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.r5hnjw5if {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.656 13.415a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rytnnmv8a {
  stop-color: var(--svg-color--f6bf99, #F6BF99);
}

.s-t2v602m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.398 9.249c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tbzx16bsb {
  d: path("M16.007 13.81c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.28-.197-.21a3 3 0 0 1-1.386.329");
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u41-5rfbj {
  d: path("m21.22 8.67l-.03-.631c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.136-.12-.368c-.256-.97.671-1.713 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uj62tebaw {
  d: path("m15.625 10.006l-.532 1.838c-.108.378.152.756.52.756h.787c.37 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.646-.408-.765 0");
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ujg3-bcoe {
  d: path("M20.61 25.809c.678-.6 1.716-.536 2.297.112l.69.734c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uuvm0cbel {
  cx: 10.18px;
  cy: 21.579px;
  r: 0.762px;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v0p7hcb9x {
  stop-color: var(--svg-color--d6927c, #D6927C);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vl91zwoht {
  cx: 9.168px;
  cy: 20.5px;
  r: 0.762px;
}

.vtlqp6_0b {
  d: path("M9.15 20.466a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.519");
}

.vzqcr0bpx {
  d: path("M18.986 10.296a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.w-gq83bca {
  stop-color: var(--svg-color--f8c4a6, #F8C4A6);
  stop-opacity: 0;
}

.w-m7nbbyp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.847c.395.01 1.357-.063 2.05-.442");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.whr7lob7j {
  d: path("M11.182 13.679a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.wjlbdbb9g {
  fill-rule: evenodd;
  d: path("M13.709 24.337a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.187l.007-.003c.516-.194 1.023.046 1.16.559c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.383l-.005.009a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x9zya81jn {
  stop-color: var(--svg-color--d8a192, #D8A192);
}

.xd7cd0__n {
  stop-color: var(--svg-color--dfa58b, #DFA58B);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xnc1jsmbn {
  fill: var(--svg-color--e1a989, #E1A989);
  d: path("m15.625 10.199l-.532 1.838c-.108.378.152.757.52.757h.787c.37 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.xnxn7_5tz {
  d: path("M18.191 9.52a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xy2hs8s1u {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.y_-nyz7qb {
  d: path("M11.39 25.809c-.678-.6-1.716-.536-2.298.112l-.69.734c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y1diaublm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.793l.907 1.18");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z67zbhbom {
  stop-color: var(--svg-color--c37b71, #C37B71);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zcstuupfv {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
  stop-opacity: 0;
}

.zgweqebwb {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.568 8.059c-.257-.185-.898-.51-1.655-.382");
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zsj5_9a3c {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.974c.78-.46 1.787-.2 2.235.546l.538.851c.048.079.043.217-.074.262c-1 .38-2.053.104-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.zsvxa8b6p {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.97 9.716a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>

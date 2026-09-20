<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":133};
const content = `<defs><linearGradient id="SVG4IWY28Ms" x1="75.7%" x2="-19.46%" y1="132.918%" y2="11.028%"><stop offset="9.1%" class="hd64_9_vu"/><stop offset="20.8%" class="dmqxzsbqx"/><stop offset="39.6%" class="m0oh6jbxt"/><stop offset="63.3%" class="itqeasb5x"/><stop offset="87.1%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVGsiwA3dsM" x1="76.46%" x2="28.669%" y1="92.419%" y2="-29.471%"><stop offset="9.1%" class="hd64_9_vu"/><stop offset="20.8%" class="dmqxzsbqx"/><stop offset="39.6%" class="m0oh6jbxt"/><stop offset="63.3%" class="itqeasb5x"/><stop offset="87.1%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVG3EVi5OZj" x1="32.174%" x2="64.565%" y1="103.685%" y2="-22.392%"><stop offset="12.3%" class="z65hc5b4d"/><stop offset="13.2%" class="bfjj85bnq"/><stop offset="21.6%" class="u41lrbbzu"/><stop offset="30.3%" class="q-040wbcf"/><stop offset="39.4%" class="gylt-sywk"/><stop offset="48.7%" class="eowrvs29n"/><stop offset="58.5%" class="nqh9dbj4y"/><stop offset="68.8%" class="v10ffzmpc"/><stop offset="80.2%" class="dir-ghb0b"/><stop offset="94.6%" class="exlv4yxxz"/></linearGradient></defs><path class="byn81rs0w"/><path fill="url(#SVG4IWY28Ms)" transform="translate(0 1.577)" class="b3wcq941d"/><path fill="url(#SVGsiwA3dsM)" transform="translate(0 1.577)" class="ooyl5tbjd"/><path fill="url(#SVG3EVi5OZj)" transform="translate(0 1.577)" class="z51nuqb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mps" /></template>
<style>
.b3wcq941d {
  d: path("M0 129.241h129.241L64.333 64.446L0 .001z");
}

.bfjj85bnq {
  stop-color: var(--svg-color--27d788, #27d788);
}

.byn81rs0w {
  d: path("M170.63 1.844h30.624l33.943 54.604L269.14 1.844h30.623v129.132h-28.225V46.671l-36.341 55.158h-.738l-35.973-54.603v83.75h-27.855zM460.163 0c18.816 0 34.866 5.902 47.964 16.417l-14.758 21.4c-11.438-7.933-22.691-12.729-33.574-12.729c-10.885 0-16.603 4.98-16.603 11.252v.37c0 5.092 1.992 8.124 8.407 10.97l.657.285q.503.213 1.04.425l.733.282l.764.283q.195.072.394.142l.812.284l.844.286l.878.287l.912.289l.946.292l.98.294l1.017.298l1.052.302l1.09.306l1.702.467l1.788.48l1.875.492l1.964.507C497.242 60.507 512 69.916 512 92.421v.37c0 25.64-19.555 40.03-47.41 40.03a82.18 82.18 0 0 1-54.79-20.661l16.788-20.108c11.622 9.593 23.797 15.68 38.556 15.68c2.137 0 4.118-.155 5.929-.457l.67-.12c7.622-1.457 12.032-5.598 12.032-11.598v-.37q0-.215-.006-.427l-.016-.419c-.233-4.293-2.362-7.32-9.423-10.356l-.699-.294l-.361-.147l-.746-.294a64 64 0 0 0-.779-.296l-.811-.296l-.845-.297l-.879-.299l-.453-.15l-.931-.302l-.967-.303l-1.003-.306l-1.04-.309l-1.079-.312l-1.115-.314l-1.155-.318l-1.194-.322l-1.234-.326l-2.824-.729l-1.527-.401l-1.504-.405l-.744-.204l-1.469-.41l-1.445-.416l-.714-.21l-1.409-.426c-20.02-6.147-32.437-14.554-32.437-36.606v-.37C414.966 15.495 433.783 0 460.162 0m-98.424 1.844c30.807 0 49.439 18.264 49.439 44.643v.368c0 29.886-23.244 45.381-52.206 45.381h-21.584v38.74h-28.409V1.844zm-2.399 25.641h-21.952v39.478h22.506c14.205 0 22.506-8.486 22.506-19.554v-.369c0-12.728-8.855-19.555-23.06-19.555");
}

.dir-ghb0b {
  stop-color: var(--svg-color--fcdc53, #fcdc53);
}

.dmqxzsbqx {
  stop-color: var(--svg-color--0d94f6, #0d94f6);
}

.eowrvs29n {
  stop-color: var(--svg-color--cadb5f, #cadb5f);
}

.exlv4yxxz {
  stop-color: var(--svg-color--ffdc52, #ffdc52);
}

.gylt-sywk {
  stop-color: var(--svg-color--abda67, #abda67);
}

.hd64_9_vu {
  stop-color: var(--svg-color--0b8fff, #0b8fff);
}

.itqeasb5x {
  stop-color: var(--svg-color--18bbb7, #18bbb7);
}

.m0oh6jbxt {
  stop-color: var(--svg-color--11a3de, #11a3de);
}

.nqh9dbj4y {
  stop-color: var(--svg-color--e1db59, #e1db59);
}

.ooyl5tbjd {
  d: path("M129.241 129.241L64.333 64.446L129.241 0z");
}

.q-040wbcf {
  stop-color: var(--svg-color--85d970, #85d970);
}

.u41lrbbzu {
  stop-color: var(--svg-color--59d87b, #59d87b);
}

.v10ffzmpc {
  stop-color: var(--svg-color--f2dc55, #f2dc55);
}

.z51nuqb7e {
  d: path("M93.947 93.947L64.333 64.446L129.241 0z");
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

</style>

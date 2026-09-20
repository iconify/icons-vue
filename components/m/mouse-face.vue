<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q-78fp1ga"/><circle class="tndzbyb6v"/><path class="ihge1ub_t"/><path class="ae7ugffll"/><path class="q3btqvefd"/><g class="k7si9abge"><path class="w78pp9b4x"/><path class="blpwx8bnf"/><path class="s7x6rbc1w"/></g><path class="yfbox9gbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mouse-face" /></template>
<style>
.ae7ugffll {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M30 18c0 7.18-8 15-12 15S6 25.18 6 18s7-9 12-9s12 1.82 12 9");
}

.blpwx8bnf {
  d: path("M32.001 35.16a1 1 0 0 1-.801-.4c-2.728-3.637-8.309-4.604-8.364-4.613a1 1 0 0 1-.822-1.15a.994.994 0 0 1 1.15-.822c.262.044 6.433 1.115 9.636 5.387a.998.998 0 0 1-.799 1.598m-31-3a.998.998 0 0 1-.515-1.857c5.244-3.146 12.355-2.175 12.656-2.133a1 1 0 0 1 .848 1.131a.997.997 0 0 1-1.13.85c-.066-.009-6.717-.909-11.345 1.867a1 1 0 0 1-.514.142");
}

.ihge1ub_t {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M13.812 10.031a5.844 5.844 0 1 1-11.688 0a5.844 5.844 0 0 1 11.688 0m20.063 0a5.844 5.844 0 1 1-11.688 0a5.844 5.844 0 0 1 11.688 0");
}

.k7si9abge {
  fill: var(--svg-color--66757f, #66757f);
}

.q-78fp1ga {
  cx: 8.5px;
  cy: 9.5px;
  r: 8.5px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.q3btqvefd {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M20.905 29.648C20.905 31.252 18.894 33 18 33s-2.905-1.748-2.905-3.352c0-1.605 1.788-1.956 2.905-1.956s2.905.351 2.905 1.956");
}

.s7x6rbc1w {
  d: path("M3.999 35.16a.999.999 0 0 1-.799-1.599c3.203-4.271 9.375-5.343 9.635-5.387a.99.99 0 0 1 1.15.821a1 1 0 0 1-.82 1.151c-.056.01-5.648.991-8.366 4.613a1 1 0 0 1-.8.401");
}

.tndzbyb6v {
  cx: 27.5px;
  cy: 9.5px;
  r: 8.5px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.w78pp9b4x {
  d: path("M34.999 32.16a1 1 0 0 1-.514-.143C29.857 29.24 23.207 30.14 23.14 30.15a.99.99 0 0 1-1.13-.85a1 1 0 0 1 .848-1.131c.301-.042 7.411-1.014 12.656 2.133a1 1 0 0 1-.515 1.858");
}

.yfbox9gbn {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M12 21s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm8 0s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2z");
}

</style>

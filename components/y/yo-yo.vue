<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="aofzzaccl"/><ellipse class="c6xjt_b1i"/><path class="z6ozdeb_c"/><ellipse class="lmsl1abkq"/><ellipse class="iv5tb16je"/><path class="fhjus9bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:yo-yo" /></template>
<style>
.aofzzaccl {
  cx: 17.722px;
  cy: 21.507px;
  fill: var(--svg-color--be1931, #be1931);
  rx: 12.917px;
  ry: 13.993px;
}

.c6xjt_b1i {
  cx: 15.569px;
  cy: 21.507px;
  fill: var(--svg-color--a0041e, #a0041e);
  rx: 12.917px;
  ry: 13.993px;
}

.fhjus9bjl {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M31.611 10.222c-2.41 0-3.889-3.398-3.889-5.833S29.176.5 31.611.5S35.5 1.954 35.5 4.389c0 2.436-1.479 5.833-3.889 5.833m0-7.778c-1.344 0-1.944.6-1.944 1.944c0 1.878 1.141 3.889 1.944 3.889s1.944-2.011 1.944-3.889c.001-1.344-.599-1.944-1.944-1.944");
}

.iv5tb16je {
  cx: 12.878px;
  cy: 21.507px;
  fill: var(--svg-color--ea596e, #ea596e);
  rx: 9.149px;
  ry: 10.433px;
}

.lmsl1abkq {
  cx: 13.417px;
  cy: 21.507px;
  fill: var(--svg-color--dd2e44, #dd2e44);
  rx: 12.917px;
  ry: 13.993px;
}

.z6ozdeb_c {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M28.298 13.741c-1.643 0-3.457-.825-5.227-1.629c-2.124-.966-4.322-1.966-5.46-1.113l-1.167-1.555c2.06-1.544 4.79-.303 7.431.898c2.023.92 4.117 1.868 5.327 1.263c.664-.331 1.155-1.195 1.459-2.566l1.899.422c-.444 2-1.259 3.27-2.49 3.885a3.9 3.9 0 0 1-1.772.395");
}

</style>

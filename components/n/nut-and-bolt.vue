<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u8a_kinlw"/><g class="l3f9bwbuw"><path class="mbmn44-zz"/><path class="qb-u5lw9z"/></g><path class="e3moynbyh"/><path class="d-q0d_hss"/><path class="kgh1v1bsw"/><path class="gslknux4h"/><path class="tw2vgqbnn"/><path class="kjaeidcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:nut-and-bolt" /></template>
<style>
.d-q0d_hss {
  fill: var(--svg-color--8b979e, #8b979e);
  d: path("M17.9 7L7.1 17.9L18 28.8L28.9 18z");
}

.e3moynbyh {
  fill: var(--svg-color--4f585b, #4f585b);
  d: path("m7.1 17.9l-7.1 7l11 11l7-7.1z");
}

.gslknux4h {
  fill: var(--svg-color--4f585b, #4f585b);
  d: path("m28.3 39.1l-7 7.1l11 10.9l7-7z");
}

.kgh1v1bsw {
  fill: var(--svg-color--cedae0, #cedae0);
  d: path("m24.9 0l-7 7l11 11l7-7z");
}

.kjaeidcfj {
  fill: var(--svg-color--cedae0, #cedae0);
  d: path("m46.2 21.3l-7 7l10.9 11l7.1-7.1z");
}

.l3f9bwbuw {
  fill: var(--svg-color--7a8891, #7a8891);
}

.mbmn44-zz {
  d: path("m64 54.6l-.5-.4l.5.5zm-10.5 8.2l1.2 1.2z");
}

.qb-u5lw9z {
  d: path("m58.7 64l5.3-3.4v-5.9l-.5-.5l-11.4 7.3l1.4 1.3l1.2 1.2zm-3.4-18l-11.4 7.3l4.1 4.1l11.4-7.3zm-8.2-8.3L35.7 45l4.1 4.1l11.4-7.2zM30.6 21.3l-11.4 7.3l4.1 4.1l11.4-7.3zm8.2 8.2l-11.4 7.3l4.1 4.1L43 33.6zM22.4 13L11 20.3l4.1 4.1l11.4-7.2z");
}

.tw2vgqbnn {
  fill: var(--svg-color--8b979e, #8b979e);
  d: path("M39.2 28.3L28.3 39.1l11 11l10.8-10.8z");
}

.u8a_kinlw {
  fill: var(--svg-color--b6c0c6, #b6c0c6);
  d: path("M58.7 64H64v-3.4zm4.8-9.8L18.4 9.1l-9.3 9.3l44.4 44.4l-1.4-1.3z");
}

</style>

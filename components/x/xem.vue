<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="buuun_odz"/><path class="my6sjbbbq"/><path class="r5tribbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xem" /></template>
<style>
.buuun_odz {
  fill: var(--svg-color--32a4f2, #32a4f2);
  d: path("M17.409 16.127a5.3 5.3 0 0 0-.657-2.61c-1.052-1.938-3.605-2.523-4.014-4.896a4.07 4.07 0 0 1 3.042-4.698c1.817-.444 3.683.564 5.22 1.43c-.016 3.902-1.375 7.582-3.591 10.774");
}

.ft5dv1b6b {
  fill: none;
}

.my6sjbbbq {
  fill: var(--svg-color--ffaa12, #ffaa12);
  d: path("M12.375 4.688a5.4 5.4 0 0 1 1.812-1.575C10.3 2.736 6.415 3.417 3 5.363c.005 2.127.17 4.864 2.191 6.046c2.27 1.327 5.274.09 5.981-2.41c.426-1.552.16-2.886 1.203-4.311");
}

.r5tribbyn {
  fill: var(--svg-color--2cbaad, #2cbaad);
  d: path("M9.957 12.572c-1.66.952-3.774.958-5.427-.01c1.526 3.48 4.168 6.524 7.47 8.425c2.295-1.355 4.858-2.96 3.898-6.048c-.74-2.496-3.702-3.646-5.94-2.367");
}

</style>

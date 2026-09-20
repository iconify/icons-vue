<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m71aoyb8l"/><path class="s_43726na"/><path class="t02ekgtrs"/><path class="ygv_0b9kh"/><path class="wyy6mfh0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:tent" /></template>
<style>
.m71aoyb8l {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M16.812 33c-.588 0-1.112-.37-1.31-.924L8.549 12.608a1.34 1.34 0 0 1 .173-1.242c.261-.369.685-.563 1.137-.563h16.313c.557 0 1.059.305 1.279.817l8.343 19.455c.184.43.14.917-.116 1.307a1.39 1.39 0 0 1-1.163.618z");
}

.s_43726na {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M1.515 33c-.467 0-.904-.236-1.162-.625a1.4 1.4 0 0 1-.116-1.315l8.348-19.479a1.392 1.392 0 0 1 2.557 0L19.49 31.06A1.39 1.39 0 0 1 18.212 33z");
}

.t02ekgtrs {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M9.859 14.182L7.077 33h5.563z");
}

.wyy6mfh0u {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M12.64 33s2.529-.645 3.766-1.786L9.859 14.182zm-5.563 0s-2.529-.645-3.766-1.786l6.546-17.031z");
}

.ygv_0b9kh {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M15.46 31.456L16.081 33H12.64zm-11.203 0L3.636 33h3.441z");
}

</style>

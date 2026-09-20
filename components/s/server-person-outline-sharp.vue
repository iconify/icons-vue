<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aonl42bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:server-person-outline-sharp" /></template>
<style>
.aonl42bhz {
  fill: currentColor;
  d: path("M5 21V3h14.02v18h-3.962l-.924-1.884h-4.25L8.962 21zm1-1h2.327l.923-1.884h5.5L15.692 20h2.327V4H6zm2.692-5.634h6.616V14.2q0-1.05-1.049-1.442T12 12.366t-2.26.392T8.693 14.2zm4.374-4.05q.434-.433.434-1.066t-.434-1.066Q12.633 7.75 12 7.75t-1.066.434T10.5 9.25t.434 1.066q.433.434 1.066.434t1.066-.434M12.02 12");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q23ffnhzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-night-rounded" /></template>
<style>
.q23ffnhzu {
  fill: currentColor;
  d: path("M9 21q-.439 0-.878-.05q-.44-.05-.855-.17q-.255-.067-.411-.28t-.156-.471q0-.156.052-.294q.052-.139.175-.25q1.462-1.53 2.267-3.452Q10 14.109 10 12t-.818-4.02q-.818-1.91-2.26-3.446q-.118-.111-.17-.25Q6.7 4.147 6.7 3.99q0-.28.153-.492t.409-.279q.42-.119.86-.169Q8.56 3 9 3q1.868 0 3.51.708t2.858 1.923t1.923 2.857t.709 3.509t-.709 3.51q-.708 1.643-1.923 2.859t-2.858 1.925T9 21");
}

</style>

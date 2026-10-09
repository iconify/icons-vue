<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxvrb1ymn.css';
import '../../css/v/vy85ju8br.css';
import '../../css/e/ejsl5db7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sxvrb1ymn"/><path class="vy85ju8br"/><path class="ejsl5db7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:time-of-use-20" /></template>

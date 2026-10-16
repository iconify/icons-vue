<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs87d4bxt.css';
import '../../css/w/wexnw_bks.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rs87d4bxt"/><path class="wexnw_bks"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:suction-bucket-20" /></template>

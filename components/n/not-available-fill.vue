<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqc_yq4_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqc_yq4_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:not-available-fill" /></template>

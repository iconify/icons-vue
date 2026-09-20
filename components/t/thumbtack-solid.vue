<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcskrwbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hcskrwbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:thumbtack-solid" /></template>

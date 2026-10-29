<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8huklp-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8huklp-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toolbox-solid" /></template>

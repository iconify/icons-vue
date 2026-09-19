<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ojc6gmg.css';
import '../../css/l/ldfs6kdmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ojc6gmg"/><path class="ldfs6kdmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:reddit" /></template>

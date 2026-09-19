<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi2bm_30d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi2bm_30d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:triangle-dashed" /></template>

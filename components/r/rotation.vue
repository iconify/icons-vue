<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awxo2eu1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awxo2eu1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rotation" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc16_k8sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc16_k8sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mushroom-fill" /></template>

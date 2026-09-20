<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8rgck7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8rgck7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shop-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9pka8qs.css';
import '../../css/d/d1k3_cc9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9pka8qs"/><path clip-rule="evenodd" class="d1k3_cc9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shop-fill" /></template>

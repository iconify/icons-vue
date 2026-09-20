<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k00bohb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k00bohb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shipment-upload-remix" /></template>

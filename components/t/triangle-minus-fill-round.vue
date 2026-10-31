<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdm-kab9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdm-kab9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-fill-round" /></template>

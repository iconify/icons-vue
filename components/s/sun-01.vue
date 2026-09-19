<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uybs10bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uybs10bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sun-01" /></template>

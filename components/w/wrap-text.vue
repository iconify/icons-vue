<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaa7_e53b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaa7_e53b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wrap-text" /></template>

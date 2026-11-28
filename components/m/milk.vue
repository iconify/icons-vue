<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1e1e9bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1e1e9bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:milk" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txgxg6k-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txgxg6k-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:presentation-line" /></template>

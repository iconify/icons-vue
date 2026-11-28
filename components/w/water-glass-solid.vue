<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7369f7ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7369f7ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:water-glass-solid" /></template>

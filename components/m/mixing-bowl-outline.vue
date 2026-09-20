<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0_ig5bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0_ig5bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mixing-bowl-outline" /></template>

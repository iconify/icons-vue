<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jomkcf3yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jomkcf3yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:reply" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs0_tbcrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs0_tbcrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring" /></template>

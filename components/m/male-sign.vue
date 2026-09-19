<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgvm7gdme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgvm7gdme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:male-sign" /></template>

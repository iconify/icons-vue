<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-8wivbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-8wivbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sliding-barndoor-closed" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xza8vabrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xza8vabrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-moon-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdfne-b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdfne-b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money4-filled" /></template>

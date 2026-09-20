<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow3vvubqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow3vvubqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:treasure" /></template>

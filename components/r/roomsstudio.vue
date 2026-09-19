<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nez8o-1lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nez8o-1lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsstudio" /></template>

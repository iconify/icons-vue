<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-i24ccuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-i24ccuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:umage-acorn" /></template>

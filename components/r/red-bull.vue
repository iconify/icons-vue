<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llu5rym_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llu5rym_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:red-bull" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjvphj5er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjvphj5er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-fuzo" /></template>

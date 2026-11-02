<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3fex56yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3fex56yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sydney-opera-house-fill" /></template>

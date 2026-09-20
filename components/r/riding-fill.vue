<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prsnft6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prsnft6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:riding-fill" /></template>

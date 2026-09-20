<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz1og7bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz1og7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-5-line" /></template>

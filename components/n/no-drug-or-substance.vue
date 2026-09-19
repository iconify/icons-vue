<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqhk5lcyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqhk5lcyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-drug-or-substance" /></template>

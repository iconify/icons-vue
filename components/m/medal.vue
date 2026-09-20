<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx90f7bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx90f7bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:medal" /></template>

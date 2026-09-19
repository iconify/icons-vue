<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmwwk298f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmwwk298f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:seal-check-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poyhed4yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poyhed4yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-3-line" /></template>

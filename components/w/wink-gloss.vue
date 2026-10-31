<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b077ofbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b077ofbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wink-gloss" /></template>

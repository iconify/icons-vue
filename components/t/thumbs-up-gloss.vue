<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd1t7_zvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd1t7_zvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-up-gloss" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoqc6bbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoqc6bbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:more-vertical-gloss" /></template>

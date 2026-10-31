<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eksos7biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eksos7biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:truck-gloss" /></template>

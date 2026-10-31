<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcfcsfbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcfcsfbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:moon-gloss" /></template>

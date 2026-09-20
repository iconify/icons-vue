<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by-fq8dre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by-fq8dre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:otto" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex6wvdbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex6wvdbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:octagon-x-gloss" /></template>

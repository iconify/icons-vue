<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejr4_1b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ejr4_1b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-solid" /></template>

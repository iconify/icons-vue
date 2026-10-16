<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhjqobksi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800};
const content = `<path class="lhjqobksi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:notary-project-light" /></template>

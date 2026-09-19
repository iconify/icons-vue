<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br--ppouu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="br--ppouu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:parallelogram" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1c4u9bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f1c4u9bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shorts" /></template>

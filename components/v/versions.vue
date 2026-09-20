<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it4ovqb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="it4ovqb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:versions" /></template>

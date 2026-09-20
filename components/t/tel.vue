<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5qgjt1uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p5qgjt1uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tel" /></template>

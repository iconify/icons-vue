<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soceu0b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="soceu0b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sauvastika-with-dots" /></template>

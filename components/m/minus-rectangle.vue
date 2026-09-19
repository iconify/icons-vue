<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbf5ltb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mbf5ltb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:minus-rectangle" /></template>

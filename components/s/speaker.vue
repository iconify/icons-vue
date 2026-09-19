<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxgthgt6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uxgthgt6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker" /></template>

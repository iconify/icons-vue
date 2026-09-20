<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxx2spbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxx2spbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:woo" /></template>

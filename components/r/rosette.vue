<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad31_4b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ad31_4b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rosette" /></template>

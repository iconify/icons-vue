<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_1w39kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty_1w39kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wasabi" /></template>

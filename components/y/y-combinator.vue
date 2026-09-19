<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfdxomh6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wfdxomh6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:y-combinator" /></template>

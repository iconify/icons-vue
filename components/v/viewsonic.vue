<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi6fgjbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200.575,"height":32.571};
const content = `<path class="hi6fgjbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:viewsonic" /></template>

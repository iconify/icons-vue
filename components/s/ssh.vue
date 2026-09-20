<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on3jn5iqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="on3jn5iqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ssh" /></template>

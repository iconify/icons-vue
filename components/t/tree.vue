<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7euacc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1792};
const content = `<path class="h7euacc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:tree" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlvupyyyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hlvupyyyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-caret-right" /></template>

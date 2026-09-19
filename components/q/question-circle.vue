<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3tqq9bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3tqq9bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:question-circle" /></template>

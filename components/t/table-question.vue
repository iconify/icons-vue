<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9zew8b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2560,"height":1472};
const content = `<path class="x9zew8b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:table-question" /></template>

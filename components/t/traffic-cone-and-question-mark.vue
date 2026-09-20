<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3c3bj8tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l3c3bj8tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:traffic-cone-and-question-mark" /></template>

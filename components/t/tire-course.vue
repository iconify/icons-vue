<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3orpionw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s3orpionw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tire-course" /></template>

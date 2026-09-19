<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3fptrb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t3fptrb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-graduate" /></template>

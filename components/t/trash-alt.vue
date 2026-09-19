<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6r2z4_ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a6r2z4_ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:trash-alt" /></template>

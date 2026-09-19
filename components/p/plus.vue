<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inpw15gqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="inpw15gqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:plus" /></template>

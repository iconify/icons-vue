<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h75qhsb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="h75qhsb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-nurse" /></template>

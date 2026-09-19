<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdyz58bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tdyz58bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:stop" /></template>

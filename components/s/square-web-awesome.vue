<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb0msfbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tb0msfbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-web-awesome" /></template>

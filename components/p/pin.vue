<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9s7qk7ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d9s7qk7ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:pin" /></template>

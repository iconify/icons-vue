<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id7306wsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="id7306wsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:refresh" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab2q78-0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ab2q78-0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:robot" /></template>

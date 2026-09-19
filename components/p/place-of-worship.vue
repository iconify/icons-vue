<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b81cd0uud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b81cd0uud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:place-of-worship" /></template>

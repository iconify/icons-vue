<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpuoa5b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpuoa5b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:user-delete" /></template>

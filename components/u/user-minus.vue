<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-yctv5li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-yctv5li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-minus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huph7acow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="huph7acow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:optistack-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvm5bl8qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wvm5bl8qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-skiing" /></template>

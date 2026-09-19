<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9kk7xjgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i9kk7xjgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:nintendo-switch" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx9oalqzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wx9oalqzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-slipping-down-steps" /></template>

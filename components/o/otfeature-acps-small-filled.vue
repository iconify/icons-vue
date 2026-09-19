<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cumjaub7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cumjaub7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-acps-small-filled" /></template>

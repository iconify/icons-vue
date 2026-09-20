<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4rw6lbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4rw6lbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:peak-design" /></template>

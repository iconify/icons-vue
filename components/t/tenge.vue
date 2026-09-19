<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgp4nsy0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qgp4nsy0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tenge" /></template>

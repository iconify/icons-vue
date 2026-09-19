<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs0poacqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zs0poacqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:old-phone" /></template>

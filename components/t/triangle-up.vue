<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzyh82htk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gzyh82htk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:triangle-up" /></template>

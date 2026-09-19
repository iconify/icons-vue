<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjeyw5bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="fjeyw5bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:youtube" /></template>

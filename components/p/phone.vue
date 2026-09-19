<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmvqur1fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vmvqur1fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:phone" /></template>

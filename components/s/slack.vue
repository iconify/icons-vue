<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls_9ogb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ls_9ogb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:slack" /></template>

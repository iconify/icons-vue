<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekqqrvb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="ekqqrvb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twitter" /></template>

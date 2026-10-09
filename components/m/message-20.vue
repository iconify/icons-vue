<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ygvf42v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2ygvf42v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-20" /></template>

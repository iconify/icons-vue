<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzvzhujzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="yzvzhujzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pen-12" /></template>

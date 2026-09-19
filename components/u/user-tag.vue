<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tis9c0sli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tis9c0sli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-tag" /></template>

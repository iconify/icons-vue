<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1e84igr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="he1e84igr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-plus" /></template>

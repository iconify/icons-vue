<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypg3n3bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ypg3n3bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:number-fill-12" /></template>

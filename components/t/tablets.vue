<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6tzagbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t6tzagbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tablets" /></template>

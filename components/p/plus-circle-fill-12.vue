<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4cai8-jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z4cai8-jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-circle-fill-12" /></template>

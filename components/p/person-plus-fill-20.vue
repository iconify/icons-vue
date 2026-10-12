<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klg708bis.css';
import '../../css/n/nib5s-byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="klg708bis"/><path class="nib5s-byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-plus-fill-20" /></template>

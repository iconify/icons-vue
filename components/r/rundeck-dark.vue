<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0gh8ac0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0gh8ac0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rundeck-dark" /></template>

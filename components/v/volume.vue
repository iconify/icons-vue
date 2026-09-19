<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd2vlzvpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":315,"height":614};
const content = `<path class="bd2vlzvpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:volume" /></template>

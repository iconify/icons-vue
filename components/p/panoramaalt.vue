<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkq5-0cbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":770};
const content = `<path class="fkq5-0cbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:panoramaalt" /></template>

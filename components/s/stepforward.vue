<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_uyzbsvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="o_uyzbsvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stepforward" /></template>

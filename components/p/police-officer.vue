<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jee2i5bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jee2i5bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:police-officer" /></template>

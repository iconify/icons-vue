<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfd3q5bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xfd3q5bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-fill-12" /></template>

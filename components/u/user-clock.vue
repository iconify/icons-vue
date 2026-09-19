<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3m98kbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="y3m98kbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-clock" /></template>

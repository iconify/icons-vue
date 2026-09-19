<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxk-lf9th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vxk-lf9th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:quidditch" /></template>

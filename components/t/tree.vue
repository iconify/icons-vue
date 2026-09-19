<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1rnrcbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1rnrcbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:tree" /></template>

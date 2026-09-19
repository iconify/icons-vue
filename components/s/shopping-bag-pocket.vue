<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj9rupc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj9rupc6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag-pocket" /></template>

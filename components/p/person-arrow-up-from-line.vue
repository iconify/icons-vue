<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c94_hxb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="c94_hxb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-arrow-up-from-line" /></template>

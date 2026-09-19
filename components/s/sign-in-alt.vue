<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p--sl88pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p--sl88pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sign-in-alt" /></template>

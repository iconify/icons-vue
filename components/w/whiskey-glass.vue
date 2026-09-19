<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy735dk7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cy735dk7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:whiskey-glass" /></template>

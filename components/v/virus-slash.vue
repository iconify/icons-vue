<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfj6xu_3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lfj6xu_3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:virus-slash" /></template>

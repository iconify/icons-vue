<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efp6-abvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="efp6-abvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mouse-pointer" /></template>

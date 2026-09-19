<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzs9lxbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yzs9lxbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:prestashop-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxp6gm95j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xxp6gm95j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sandbox-stroke-20" /></template>

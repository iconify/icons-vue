<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8i5lmblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k8i5lmblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-jumping-on-bouncy-cushion" /></template>

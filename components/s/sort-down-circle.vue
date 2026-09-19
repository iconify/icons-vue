<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-xpobs9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q-xpobs9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sort-down-circle" /></template>

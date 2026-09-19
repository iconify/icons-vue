<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfjqfsb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfjqfsb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:remove-outline" /></template>

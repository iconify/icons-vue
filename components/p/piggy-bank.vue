<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwz0i-bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":472};
const content = `<path class="xwz0i-bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:piggy-bank" /></template>

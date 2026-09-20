<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgwvay-0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tgwvay-0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:up-outline" /></template>

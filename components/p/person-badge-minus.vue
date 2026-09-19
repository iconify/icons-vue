<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdk_v4oev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wdk_v4oev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-badge-minus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h__prbc9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h__prbc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-badge-minus" /></template>

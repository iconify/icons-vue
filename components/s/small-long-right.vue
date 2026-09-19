<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lebys2svk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lebys2svk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:small-long-right" /></template>

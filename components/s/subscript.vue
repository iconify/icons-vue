<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsg9ixp1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsg9ixp1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:subscript" /></template>

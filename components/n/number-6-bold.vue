<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/argz2yb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="argz2yb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-bold" /></template>

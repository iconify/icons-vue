<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr-3k3jjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-3k3jjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-x" /></template>

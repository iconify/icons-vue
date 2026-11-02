<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krlfzsbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krlfzsbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trunk-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipovzzbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipovzzbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-from-bottom-to-top-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh8z32gqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh8z32gqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:unfold-less" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0g97kztd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0g97kztd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pig-filled" /></template>

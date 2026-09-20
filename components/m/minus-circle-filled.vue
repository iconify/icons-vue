<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ggx5n0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8ggx5n0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-circle-filled" /></template>

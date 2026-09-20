<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td5fekbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="td5fekbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slash-circle-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orz84zbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orz84zbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:split-filled" /></template>

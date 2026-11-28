<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poupq6bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poupq6bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:snapchat-solid" /></template>

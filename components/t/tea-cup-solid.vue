<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq6ae5uin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cq6ae5uin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tea-cup-solid" /></template>

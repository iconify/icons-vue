<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlpmq0bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlpmq0bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tree-alt-filled" /></template>

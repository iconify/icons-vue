<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a94572moh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a94572moh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:signal-alt-3" /></template>

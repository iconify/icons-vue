<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk0hgq-4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk0hgq-4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pickaxe-solid" /></template>

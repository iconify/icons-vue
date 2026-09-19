<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8r359d7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8r359d7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:unfold-less" /></template>

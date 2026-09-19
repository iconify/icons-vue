<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4sh_8-va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4sh_8-va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:ticket" /></template>

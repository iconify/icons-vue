<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y08iq0bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y08iq0bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:sort-size-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0e7lzicz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0e7lzicz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minus-duotone" /></template>

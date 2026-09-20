<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izh_tfbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="izh_tfbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-left" /></template>

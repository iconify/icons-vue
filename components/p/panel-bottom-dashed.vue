<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0m-cfizf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0m-cfizf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-dashed" /></template>

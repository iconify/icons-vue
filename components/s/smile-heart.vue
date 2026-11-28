<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoz23tbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoz23tbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smile-heart" /></template>

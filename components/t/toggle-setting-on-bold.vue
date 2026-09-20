<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9uy6eb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9uy6eb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:toggle-setting-on-bold" /></template>

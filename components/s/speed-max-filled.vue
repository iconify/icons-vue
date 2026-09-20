<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6o3i5n4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6o3i5n4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:speed-max-filled" /></template>

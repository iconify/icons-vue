<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgmc-yboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgmc-yboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server4-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48_7mbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i48_7mbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag" /></template>

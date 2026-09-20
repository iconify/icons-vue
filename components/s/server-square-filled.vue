<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbpwy0b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbpwy0b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-square-filled" /></template>

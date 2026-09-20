<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h__6adbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h__6adbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-filled" /></template>

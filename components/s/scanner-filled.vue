<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3c-a52sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3c-a52sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scanner-filled" /></template>

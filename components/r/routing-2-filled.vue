<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su9e4nbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="su9e4nbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:routing-2-filled" /></template>

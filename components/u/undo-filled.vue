<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn6c7gbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zn6c7gbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:undo-filled" /></template>

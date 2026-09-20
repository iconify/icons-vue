<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z42twibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z42twibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pause-circle-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no308zbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no308zbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paperclip-2" /></template>

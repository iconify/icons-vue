<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjmvz6bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjmvz6bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-2-fill" /></template>

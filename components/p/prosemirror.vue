<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm535xbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm535xbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:prosemirror" /></template>

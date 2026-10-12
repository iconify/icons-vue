<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4yu8j-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yt4yu8j-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rugby-ball-filled" /></template>

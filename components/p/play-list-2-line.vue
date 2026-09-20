<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdb3384up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdb3384up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-list-2-line" /></template>

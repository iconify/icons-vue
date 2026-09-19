<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_tqzxbbs.css';
import '../../css/d/dp4lw14sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tqzxbbs"/><path class="dp4lw14sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:sticker" /></template>

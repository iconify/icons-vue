<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxjbrub3m.css';
import '../../css/b/bcedl12ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jxjbrub3m"/><circle class="bcedl12ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-chat-rtl" /></template>

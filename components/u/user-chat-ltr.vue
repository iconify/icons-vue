<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiiytincm.css';
import '../../css/g/g8ll7b7pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uiiytincm"/><circle class="g8ll7b7pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-chat-ltr" /></template>

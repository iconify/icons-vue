<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5v5asbue.css';
import '../../css/d/djipz6cyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5v5asbue"/><path class="djipz6cyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-star" /></template>

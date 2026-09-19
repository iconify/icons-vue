<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj008nblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj008nblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:telegram-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iayn1llfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iayn1llfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:paperclip" /></template>

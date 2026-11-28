<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3sa77ogg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary r3sa77ogg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paperclip-duotone" /></template>

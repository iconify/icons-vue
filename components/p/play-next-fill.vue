<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oks3pobcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oks3pobcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-next-fill" /></template>

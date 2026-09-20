<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fymhyv7jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fymhyv7jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:unfold-more" /></template>

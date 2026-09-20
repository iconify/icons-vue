<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joyz7rb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joyz7rb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-first" /></template>

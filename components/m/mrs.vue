<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoyo56b2a.css';
import '../../css/o/ogduviblr.css';
import '../../css/b/bx9w9rkcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoyo56b2a"/><path class="ogduviblr"/><path class="bx9w9rkcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mrs" /></template>

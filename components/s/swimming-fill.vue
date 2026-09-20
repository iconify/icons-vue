<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1hgb6bzy.css';
import '../../css/f/fj3ryr4ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1hgb6bzy"/><path class="fj3ryr4ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:swimming-fill" /></template>

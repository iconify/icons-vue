<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja48t5b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ja48t5b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-waves" /></template>

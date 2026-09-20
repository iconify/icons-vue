<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efwa3rb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efwa3rb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sswp" /></template>

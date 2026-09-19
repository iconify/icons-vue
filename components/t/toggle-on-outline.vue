<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4s7832oy.css';
import '../../css/a/alcoyobza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4s7832oy"/><path clip-rule="evenodd" class="alcoyobza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:toggle-on-outline" /></template>

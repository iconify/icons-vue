<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8j6e2bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8j6e2bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playlist-fill" /></template>

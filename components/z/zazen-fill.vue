<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asspptbxz.css';
import '../../css/b/bbvbykbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asspptbxz"/><path clip-rule="evenodd" class="bbvbykbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zazen-fill" /></template>

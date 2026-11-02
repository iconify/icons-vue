<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8gzh9bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8gzh9bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nfc-fill" /></template>

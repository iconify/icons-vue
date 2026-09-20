<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3_df9_ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3_df9_ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wheelchair-fill" /></template>

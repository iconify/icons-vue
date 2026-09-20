<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwxqwobia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wwxqwobia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telescope-2-fill" /></template>

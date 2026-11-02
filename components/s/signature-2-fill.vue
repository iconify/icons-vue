<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f15xpgbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f15xpgbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-2-fill" /></template>

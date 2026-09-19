<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lor7kcbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lor7kcbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:pill" /></template>

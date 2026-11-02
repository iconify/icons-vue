<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9u4854ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9u4854ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandstorm-fill" /></template>

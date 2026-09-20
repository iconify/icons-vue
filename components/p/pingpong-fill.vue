<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaj94ab-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaj94ab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pingpong-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3k9a95ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3k9a95ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:necktie-line" /></template>

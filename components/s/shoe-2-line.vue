<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlv3huuyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlv3huuyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shoe-2-line" /></template>

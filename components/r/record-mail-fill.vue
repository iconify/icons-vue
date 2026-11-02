<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orz21ab4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orz21ab4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:record-mail-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5nl78bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5nl78bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:unfold" /></template>

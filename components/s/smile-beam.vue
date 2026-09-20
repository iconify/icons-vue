<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_dc70buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_dc70buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:smile-beam" /></template>

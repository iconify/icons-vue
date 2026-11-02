<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djlpdi26g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djlpdi26g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moonlight-fill" /></template>

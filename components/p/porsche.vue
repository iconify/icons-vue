<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he82iqb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he82iqb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:porsche" /></template>

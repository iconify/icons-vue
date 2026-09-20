<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgajuu1ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgajuu1ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-2-fill" /></template>

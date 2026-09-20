<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga065kb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga065kb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tkn" /></template>

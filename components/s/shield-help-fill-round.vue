<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4a2-bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw4a2-bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-help-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk_4r9bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_4r9bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soup-fill-round" /></template>

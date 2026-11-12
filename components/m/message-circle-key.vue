<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq-l9svud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-l9svud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-key" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_15pbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_15pbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pause-round" /></template>

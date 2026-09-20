<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elp8hoo8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elp8hoo8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:part" /></template>

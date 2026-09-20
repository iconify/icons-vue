<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltu75mm9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltu75mm9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:paperclip" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n98i4bxrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n98i4bxrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-lock-fill" /></template>

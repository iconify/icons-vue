<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p70oy3bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p70oy3bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:pentagon-fill" /></template>

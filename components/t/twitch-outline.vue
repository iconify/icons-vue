<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1q_xb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1q_xb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:twitch-outline" /></template>

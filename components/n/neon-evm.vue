<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7zfzl34q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7zfzl34q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:neon-evm" /></template>

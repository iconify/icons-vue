<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaix50b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaix50b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-2-fill" /></template>

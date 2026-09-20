<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh8x5liyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qh8x5liyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-round-outline" /></template>

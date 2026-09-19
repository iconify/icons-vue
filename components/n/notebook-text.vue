<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-grcwq2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-grcwq2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notebook-text" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5fjhy4ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5fjhy4ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-arrow-solid" /></template>

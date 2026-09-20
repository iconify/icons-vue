<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evzh2560b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evzh2560b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:microphone-2-off" /></template>

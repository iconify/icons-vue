<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyrdbnm5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyrdbnm5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wav-01" /></template>

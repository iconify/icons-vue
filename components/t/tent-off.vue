<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2fzirb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2fzirb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tent-off" /></template>

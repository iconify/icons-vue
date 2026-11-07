<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcuss6sft.css';
import '../../css/a/arfojkbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcuss6sft"/><path clip-rule="evenodd" class="arfojkbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruble-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s64hfearz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s64hfearz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paper-bin-outline" /></template>

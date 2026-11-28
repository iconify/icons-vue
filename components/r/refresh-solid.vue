<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt2wc0bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt2wc0bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:refresh-solid" /></template>

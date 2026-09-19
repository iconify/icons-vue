<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvwqf0b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvwqf0b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-delivered-01" /></template>

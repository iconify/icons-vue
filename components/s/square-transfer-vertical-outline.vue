<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whogh4bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whogh4bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-transfer-vertical-outline" /></template>

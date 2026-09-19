<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9mqcmbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9mqcmbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:recycle-01" /></template>

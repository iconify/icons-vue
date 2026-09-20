<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ifmhbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ifmhbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-3-fill" /></template>

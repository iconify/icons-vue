<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l55_2bcdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l55_2bcdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-4-fill" /></template>

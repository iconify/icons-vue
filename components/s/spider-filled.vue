<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wghzu7b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wghzu7b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spider-filled" /></template>

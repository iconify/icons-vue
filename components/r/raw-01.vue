<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo9268es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puo9268es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:raw-01" /></template>

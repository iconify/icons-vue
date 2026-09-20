<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw7p2hb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw7p2hb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swiss-cheese" /></template>

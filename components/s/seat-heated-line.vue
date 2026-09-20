<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuub4hb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuub4hb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seat-heated-line" /></template>

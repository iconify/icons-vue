<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zpdgb-u.css';
import '../../css/f/fuln-e3lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zpdgb-u"/><path class="fuln-e3lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:satellite-dish-filled" /></template>

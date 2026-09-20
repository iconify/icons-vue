<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b21_4_b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b21_4_b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-medium-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a89e9bchg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a89e9bchg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:view-grid" /></template>

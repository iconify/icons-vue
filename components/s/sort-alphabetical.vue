<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e50zsvy-u.css';
import '../../css/f/f-c4afb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="e50zsvy-u"/><path class="f-c4afb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sort-alphabetical" /></template>

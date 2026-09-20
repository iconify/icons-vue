<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x61jlibhq.css';
import '../../css/r/r9bbvybua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x61jlibhq"/><path clip-rule="evenodd" class="r9bbvybua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:slam" /></template>

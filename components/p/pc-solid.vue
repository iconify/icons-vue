<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7h8fb2z.css';
import '../../css/c/cega53b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7h8fb2z"/><path class="cega53b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pc-solid" /></template>

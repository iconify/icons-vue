<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/runyxf3yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="runyxf3yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more" /></template>

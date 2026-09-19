<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8w73bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg8w73bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sliding-window-door-open" /></template>

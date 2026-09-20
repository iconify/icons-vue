<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p08cbk-fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p08cbk-fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:man-filled" /></template>

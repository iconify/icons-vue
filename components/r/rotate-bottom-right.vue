<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob843kbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob843kbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-bottom-right" /></template>

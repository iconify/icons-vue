<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzcs35b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzcs35b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:two-finger-05" /></template>

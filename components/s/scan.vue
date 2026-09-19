<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5g5b5b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5g5b5b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scan" /></template>

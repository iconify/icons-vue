<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8sq1b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg8sq1b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rain" /></template>

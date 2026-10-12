<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0sb-0bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0sb-0bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mic-signal-filled" /></template>

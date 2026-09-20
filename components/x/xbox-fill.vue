<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb1rxtbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb1rxtbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xbox-fill" /></template>

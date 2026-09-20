<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okshilb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okshilb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:usd-circle" /></template>

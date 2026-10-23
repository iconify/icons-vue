<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z23dvnbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z23dvnbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-round-corner" /></template>

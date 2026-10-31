<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1r3hmb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1r3hmb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-horizontal-round" /></template>

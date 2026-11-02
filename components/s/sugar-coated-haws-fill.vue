<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlwo-kb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlwo-kb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sugar-coated-haws-fill" /></template>

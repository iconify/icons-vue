<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls27mabel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls27mabel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-symbols" /></template>

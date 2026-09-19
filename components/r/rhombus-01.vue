<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr1rmrbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr1rmrbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rhombus-01" /></template>

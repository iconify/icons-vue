<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt6zanb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt6zanb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:maximize-left" /></template>

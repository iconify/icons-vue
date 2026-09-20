<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmzbrk_2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmzbrk_2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:route-square-2" /></template>

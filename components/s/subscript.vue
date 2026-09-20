<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3e4w2dth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3e4w2dth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:subscript" /></template>

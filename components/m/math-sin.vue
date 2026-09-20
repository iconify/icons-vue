<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9gn9xbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9gn9xbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-sin" /></template>

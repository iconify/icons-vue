<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of-f3g3uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of-f3g3uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-3-line" /></template>

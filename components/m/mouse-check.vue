<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa-cuqjev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa-cuqjev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mouse-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwdyy_0gr.css';
import '../../css/j/jdu2jtbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdyy_0gr"/><path class="jdu2jtbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-horizontal-bold-duotone" /></template>

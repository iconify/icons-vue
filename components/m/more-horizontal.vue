<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds25a98oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds25a98oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-horizontal" /></template>

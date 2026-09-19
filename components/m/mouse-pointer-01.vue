<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmxstrbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmxstrbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-pointer-01" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3l-flb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3l-flb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-nyro" /></template>

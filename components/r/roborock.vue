<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpfc-j4bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpfc-j4bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roborock" /></template>

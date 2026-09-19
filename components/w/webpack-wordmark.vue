<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9vv6pb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p9vv6pb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:webpack-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcp-osn-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcp-osn-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-spline" /></template>

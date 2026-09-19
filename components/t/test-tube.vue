<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvju54b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="qvju54b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:test-tube" /></template>

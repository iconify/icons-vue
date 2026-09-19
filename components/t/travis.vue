<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yux5wj47h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yux5wj47h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:travis" /></template>

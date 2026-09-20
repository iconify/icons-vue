<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw23e5btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw23e5btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-3-line" /></template>

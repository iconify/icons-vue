<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uatu1gbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="uatu1gbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-store" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-n03pbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-n03pbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:stop-24" /></template>

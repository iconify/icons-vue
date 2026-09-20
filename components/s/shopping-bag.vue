<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn05zjzoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn05zjzoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag" /></template>

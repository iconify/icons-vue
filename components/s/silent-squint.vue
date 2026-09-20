<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jagb8r3zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jagb8r3zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:silent-squint" /></template>

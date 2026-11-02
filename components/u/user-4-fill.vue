<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmxt5nb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmxt5nb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-4-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-he1cpls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-he1cpls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parachute-fill" /></template>

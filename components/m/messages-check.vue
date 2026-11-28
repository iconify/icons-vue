<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0l-vlv5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0l-vlv5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:messages-check" /></template>

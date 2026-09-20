<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr3krrblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3krrblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:meh-closed-eye" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrua-sjqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrua-sjqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:more" /></template>

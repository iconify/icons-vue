<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi27grjzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi27grjzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:reload-expressive" /></template>

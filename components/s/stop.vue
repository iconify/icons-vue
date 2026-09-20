<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t90x8mbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t90x8mbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:stop" /></template>

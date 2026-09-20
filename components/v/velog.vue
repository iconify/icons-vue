<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hotlcw4rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hotlcw4rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:velog" /></template>

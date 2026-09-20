<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmv89ubjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmv89ubjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wistia" /></template>

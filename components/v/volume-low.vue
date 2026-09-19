<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m22ynacqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m22ynacqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:volume-low" /></template>

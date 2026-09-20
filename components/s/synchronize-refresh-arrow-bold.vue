<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3cr_w9fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cr_w9fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:synchronize-refresh-arrow-bold" /></template>

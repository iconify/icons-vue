<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_a40-blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_a40-blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-econic-lantern" /></template>

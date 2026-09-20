<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e32-4cb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e32-4cb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz9ww4b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz9ww4b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-right2" /></template>

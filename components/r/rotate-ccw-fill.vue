<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqlz9tzcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqlz9tzcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0o-9gngb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0o-9gngb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:webcam-off" /></template>

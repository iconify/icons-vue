<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c22yatb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c22yatb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-lock-open" /></template>

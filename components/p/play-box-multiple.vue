<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0jbyb2bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0jbyb2bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-multiple" /></template>

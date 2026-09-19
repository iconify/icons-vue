<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3vajob_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3vajob_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:save-1" /></template>

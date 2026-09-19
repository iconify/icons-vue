<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0haz65-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0haz65-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:triangle" /></template>

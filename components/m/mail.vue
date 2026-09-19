<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3yk7pb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="v3yk7pb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:mail" /></template>

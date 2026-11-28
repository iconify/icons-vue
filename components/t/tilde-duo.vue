<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbl7l1byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl7l1byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tilde-duo" /></template>

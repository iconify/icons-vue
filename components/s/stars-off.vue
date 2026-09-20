<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_f9mwv7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_f9mwv7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stars-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9zq__yqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9zq__yqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-solid" /></template>

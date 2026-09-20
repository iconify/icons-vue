<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0qd9kuvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0qd9kuvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tooth-fill" /></template>

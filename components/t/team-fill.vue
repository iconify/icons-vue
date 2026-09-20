<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh_x4nf4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh_x4nf4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:team-fill" /></template>

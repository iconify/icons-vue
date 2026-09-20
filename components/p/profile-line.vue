<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq5mdzb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq5mdzb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:profile-line" /></template>

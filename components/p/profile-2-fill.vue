<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa1gi8eew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa1gi8eew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:profile-2-fill" /></template>

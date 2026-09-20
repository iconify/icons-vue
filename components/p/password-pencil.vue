<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lks5r8mvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lks5r8mvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-pencil" /></template>

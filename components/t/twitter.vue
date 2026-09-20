<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9993z9uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9993z9uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:twitter" /></template>

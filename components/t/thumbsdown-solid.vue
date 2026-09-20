<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdrf1fb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrf1fb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:thumbsdown-solid" /></template>

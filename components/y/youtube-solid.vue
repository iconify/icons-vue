<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhz3anl9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhz3anl9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:youtube-solid" /></template>

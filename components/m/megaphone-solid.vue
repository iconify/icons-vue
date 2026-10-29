<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl-c-h5mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl-c-h5mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:megaphone-solid" /></template>

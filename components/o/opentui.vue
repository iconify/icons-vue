<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6yg68r2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6yg68r2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opentui" /></template>

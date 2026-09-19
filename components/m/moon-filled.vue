<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lodm-2b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lodm-2b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:moon-filled" /></template>

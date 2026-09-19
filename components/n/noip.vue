<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu-6n5ags.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu-6n5ags"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:noip" /></template>

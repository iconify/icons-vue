<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-s4f8x0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a-s4f8x0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:speaker-mute-16" /></template>

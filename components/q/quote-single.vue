<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3-o5s18u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3-o5s18u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-single" /></template>

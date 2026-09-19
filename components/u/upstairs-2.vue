<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jth9mfb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jth9mfb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:upstairs-2" /></template>

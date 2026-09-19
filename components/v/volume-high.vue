<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lti3lcbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lti3lcbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:volume-high" /></template>

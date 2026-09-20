<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa7ihwbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa7ihwbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:peertube" /></template>

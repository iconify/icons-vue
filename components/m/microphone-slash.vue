<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqve-bc3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="mqve-bc3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:microphone-slash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjwn39bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":512};
const content = `<path class="jjwn39bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:miranda" /></template>

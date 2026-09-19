<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vot768pgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":497,"height":512};
const content = `<path class="vot768pgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:powerbuilder" /></template>

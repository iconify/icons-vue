<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftw-gh2gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftw-gh2gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-forwarded" /></template>

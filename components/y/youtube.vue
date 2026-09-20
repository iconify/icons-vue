<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyi7gccyf.css';
import '../../css/u/u86mi1b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyi7gccyf"/><path class="u86mi1b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:youtube" /></template>

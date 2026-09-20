<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv7-q-1vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv7-q-1vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:windows-fill" /></template>

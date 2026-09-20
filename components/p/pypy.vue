<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi-tv3b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi-tv3b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pypy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up92zwb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up92zwb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mailgun" /></template>

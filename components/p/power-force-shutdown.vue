<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjcmjo8jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjcmjo8jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:power-force-shutdown" /></template>

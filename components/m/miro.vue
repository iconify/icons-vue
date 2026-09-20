<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abc94bc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abc94bc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:miro" /></template>

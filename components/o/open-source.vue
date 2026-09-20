<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv0z9ub6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv0z9ub6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:open-source" /></template>

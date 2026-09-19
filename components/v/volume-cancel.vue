<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q49gzmb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q49gzmb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-cancel" /></template>

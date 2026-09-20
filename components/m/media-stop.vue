<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk6vc83tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6vc83tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-stop" /></template>

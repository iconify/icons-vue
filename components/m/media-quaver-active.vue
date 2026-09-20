<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omh5kl7yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omh5kl7yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-quaver-active" /></template>

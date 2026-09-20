<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/varr8acvu.css';
import '../../css/n/nk4n3vbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="varr8acvu"/><path class="nk4n3vbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-file-adobe-bold" /></template>

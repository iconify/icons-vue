<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nldaqvbfh.css';
import '../../css/g/g4qvddbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nldaqvbfh"/><path class="g4qvddbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-round-alt-filled" /></template>

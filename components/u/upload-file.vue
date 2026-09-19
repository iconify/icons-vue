<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmwpenbhg.css';
import '../../css/i/i4bpspa_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pmwpenbhg"/><path class="duoicon-primary-layer i4bpspa_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:upload-file" /></template>

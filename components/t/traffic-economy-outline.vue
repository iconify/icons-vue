<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exsf8gejx.css';
import '../../css/x/x8863dbnx.css';
import '../../css/r/rgo7s3bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exsf8gejx"/><path class="x8863dbnx"/><path class="rgo7s3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-economy-outline" /></template>

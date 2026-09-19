<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq306tmap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq306tmap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:status-unknown" /></template>

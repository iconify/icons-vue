<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxg8xs31d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxg8xs31d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ory" /></template>

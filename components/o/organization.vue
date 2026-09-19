<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si8xjubph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si8xjubph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:organization" /></template>

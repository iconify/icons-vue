<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn560_avf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn560_avf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:threats" /></template>

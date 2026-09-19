<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcimb-b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcimb-b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:network-drive" /></template>

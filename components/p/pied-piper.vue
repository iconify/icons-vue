<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfw1rib9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfw1rib9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:pied-piper" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coomk31qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coomk31qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:monospace" /></template>

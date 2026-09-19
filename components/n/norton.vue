<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea1bd19wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1bd19wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:norton" /></template>

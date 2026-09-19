<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdvy41q8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdvy41q8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:next" /></template>

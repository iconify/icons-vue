<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rneo-_btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rneo-_btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:toolbox" /></template>

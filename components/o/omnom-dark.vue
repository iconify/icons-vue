<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btiw_o-yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btiw_o-yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnom-dark" /></template>

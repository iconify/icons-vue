<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlxz3cbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlxz3cbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-fastforward" /></template>

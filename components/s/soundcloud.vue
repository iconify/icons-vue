<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vst2324hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vst2324hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:soundcloud" /></template>

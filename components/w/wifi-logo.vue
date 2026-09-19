<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mds117d_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="mds117d_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wifi-logo" /></template>

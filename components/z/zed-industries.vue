<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl2p6pedi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl2p6pedi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zed-industries" /></template>

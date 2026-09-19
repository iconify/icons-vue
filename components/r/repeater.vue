<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vto2pjblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vto2pjblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:repeater" /></template>

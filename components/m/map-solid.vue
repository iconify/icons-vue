<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqa7o6dfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqa7o6dfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:map-solid" /></template>

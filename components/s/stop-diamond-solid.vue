<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbj-hzbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbj-hzbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-diamond-solid" /></template>

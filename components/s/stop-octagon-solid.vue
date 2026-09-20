<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bml1_1bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bml1_1bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-octagon-solid" /></template>

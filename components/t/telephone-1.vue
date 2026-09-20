<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wllv4abeh.css';
import '../../css/u/ui1cszbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wllv4abeh"/><path class="ui1cszbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:telephone-1" /></template>

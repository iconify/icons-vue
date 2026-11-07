<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzflwis8e.css';
import '../../css/a/a-jc6dbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzflwis8e"/><path clip-rule="evenodd" class="a-jc6dbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-wave-bold" /></template>

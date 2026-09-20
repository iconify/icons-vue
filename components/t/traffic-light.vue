<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm7z09bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm7z09bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:traffic-light" /></template>

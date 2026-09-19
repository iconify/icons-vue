<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_kj5lbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_kj5lbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sunsynk" /></template>

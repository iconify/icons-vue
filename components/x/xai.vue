<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_d6vc2qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_d6vc2qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xai" /></template>

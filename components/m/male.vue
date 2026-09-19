<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_7njbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="gf_7njbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:male" /></template>

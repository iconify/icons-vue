<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glo_rsb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glo_rsb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:southwest-airlines" /></template>

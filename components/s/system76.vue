<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udjtoqb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udjtoqb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:system76" /></template>

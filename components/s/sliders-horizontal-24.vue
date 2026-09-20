<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf53lvbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf53lvbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sliders-horizontal-24" /></template>

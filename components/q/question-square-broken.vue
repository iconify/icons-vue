<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iwfsg6b7f.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/p/pr1jznbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iwfsg6b7f"/><path class="si_mtzbvj"/><path class="pr1jznbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-square-broken" /></template>

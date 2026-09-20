<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4p5vacnv.css';
import '../../css/v/v1l1tsapd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4p5vacnv"/><path class="v1l1tsapd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shield-check-duotone" /></template>

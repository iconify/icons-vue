<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwqf32bdv.css';
import '../../css/u/u48ityuik.css';
import '../../css/v/vxml6xbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwqf32bdv"/><path class="u48ityuik"/><path class="vxml6xbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:radar" /></template>

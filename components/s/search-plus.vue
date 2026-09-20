<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n82zcy6-h.css';
import '../../css/c/cwu8tob-z.css';
import '../../css/n/nwzo9bcnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n82zcy6-h"/><path class="cwu8tob-z"/><path class="nwzo9bcnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:search-plus" /></template>

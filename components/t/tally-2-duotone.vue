<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvh_n7eff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qvh_n7eff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-2-duotone" /></template>

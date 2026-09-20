<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jva7wh10t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jva7wh10t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-last-fm-circular" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-ab2_gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh-ab2_gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:phone-shake" /></template>

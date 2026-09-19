<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1une9bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1une9bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:phone-forwarded" /></template>

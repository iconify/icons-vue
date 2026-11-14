<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j70k80t2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j70k80t2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-asterisk" /></template>

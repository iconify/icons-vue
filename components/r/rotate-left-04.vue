<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5lrmtgqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5lrmtgqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-left-04" /></template>

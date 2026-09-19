<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olt19cb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olt19cb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-unlock-01" /></template>

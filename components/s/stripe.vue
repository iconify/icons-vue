<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3_p6ob_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3_p6ob_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stripe" /></template>

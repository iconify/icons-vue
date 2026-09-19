<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvs_ubbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvs_ubbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:svg-01" /></template>

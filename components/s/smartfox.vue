<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m56_hyqyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m56_hyqyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smartfox" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiqh8os_h.css';
import '../../css/t/tgl2ebb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqh8os_h"/><path class="tgl2ebb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sliders-v-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2hcgcc2r.css';
import '../../css/m/mwvb097_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2hcgcc2r"/><path class="mwvb097_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:people-group" /></template>

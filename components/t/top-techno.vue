<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ocm_bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_ocm_bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:top-techno" /></template>

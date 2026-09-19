<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spqsm_b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spqsm_b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wix" /></template>

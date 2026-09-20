<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrc4qfb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrc4qfb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:opera-gx" /></template>

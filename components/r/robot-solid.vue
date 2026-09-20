<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9yj1rs4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9yj1rs4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:robot-solid" /></template>

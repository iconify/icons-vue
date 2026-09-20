<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnae_cc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnae_cc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:subject" /></template>

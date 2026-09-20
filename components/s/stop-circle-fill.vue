<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiv-qtb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiv-qtb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stop-circle-fill" /></template>

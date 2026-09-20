<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf8a_mbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf8a_mbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:veeam" /></template>

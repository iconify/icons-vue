<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_l3fw_0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_l3fw_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufuc2cbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufuc2cbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safety-certificate-fill" /></template>

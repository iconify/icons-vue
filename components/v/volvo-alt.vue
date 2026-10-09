<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ychg3ko0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ychg3ko0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo-alt" /></template>

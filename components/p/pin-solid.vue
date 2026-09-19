<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8nbc4jxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8nbc4jxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:pin-solid" /></template>

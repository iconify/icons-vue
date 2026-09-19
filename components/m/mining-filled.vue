<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnz306bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnz306bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:mining-filled" /></template>

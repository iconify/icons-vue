<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlfi_1iqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlfi_1iqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:secure-data" /></template>

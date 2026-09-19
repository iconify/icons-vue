<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thdk2kbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thdk2kbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-connected-02" /></template>

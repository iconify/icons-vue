<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd_fl2b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_fl2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:printer-off-solid" /></template>

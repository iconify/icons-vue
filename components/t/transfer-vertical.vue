<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu0re_lux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu0re_lux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transfer-vertical" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqx_ffbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqx_ffbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wink-tv" /></template>

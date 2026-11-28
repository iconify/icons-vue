<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btdpvss2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btdpvss2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wine-crack-solid" /></template>

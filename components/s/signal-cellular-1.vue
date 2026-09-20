<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smf9jihll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smf9jihll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-cellular-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwi4gopza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwi4gopza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yeelight-beside-lamp" /></template>

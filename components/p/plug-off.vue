<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqcy64bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqcy64bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plug-off" /></template>

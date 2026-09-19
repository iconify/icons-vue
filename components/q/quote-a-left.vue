<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg6qipopk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="tg6qipopk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:quote-a-left" /></template>

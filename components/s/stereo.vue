<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcq5rub-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcq5rub-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stereo" /></template>

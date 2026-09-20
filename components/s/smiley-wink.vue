<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl7o9-bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl7o9-bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smiley-wink" /></template>

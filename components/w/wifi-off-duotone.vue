<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcq4rebkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vcq4rebkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wifi-off-duotone" /></template>

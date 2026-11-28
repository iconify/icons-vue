<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlp59pc0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlp59pc0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:messages-circle-solid" /></template>

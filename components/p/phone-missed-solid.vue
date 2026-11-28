<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubg3ixvlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubg3ixvlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-missed-solid" /></template>

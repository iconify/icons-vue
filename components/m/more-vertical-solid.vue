<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu-2ao_sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu-2ao_sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:more-vertical-solid" /></template>

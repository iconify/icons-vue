<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6ouwebbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s6ouwebbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wheat-duotone" /></template>

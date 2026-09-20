<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhp1ik06l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhp1ik06l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:umbrella-off" /></template>

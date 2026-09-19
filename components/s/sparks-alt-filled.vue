<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awh978bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awh978bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sparks-alt-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g32-skbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g32-skbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:natural-disaster-flood-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo3hdprsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo3hdprsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:soundwave-outline" /></template>

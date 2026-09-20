<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv62uor1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv62uor1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-in-alt-duotone" /></template>

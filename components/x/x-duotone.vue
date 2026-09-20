<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0zm1bcnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0zm1bcnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:x-duotone" /></template>

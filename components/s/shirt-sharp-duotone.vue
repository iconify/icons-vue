<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tttpw3btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tttpw3btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shirt-sharp-duotone" /></template>

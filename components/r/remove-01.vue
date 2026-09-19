<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_7twlpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh_7twlpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-01" /></template>

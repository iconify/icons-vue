<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui5hz-rai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui5hz-rai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ship-filled" /></template>

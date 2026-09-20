<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zte3mqbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zte3mqbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-plus" /></template>

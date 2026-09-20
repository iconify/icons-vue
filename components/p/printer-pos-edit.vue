<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rffkmacri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rffkmacri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-pos-edit" /></template>

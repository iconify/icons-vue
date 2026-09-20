<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgdmczbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgdmczbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speaker-wireless" /></template>

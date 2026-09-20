<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psv555bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psv555bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:router-wifi-network-remix" /></template>

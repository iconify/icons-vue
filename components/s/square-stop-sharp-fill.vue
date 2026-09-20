<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq7wydr-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq7wydr-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-stop-sharp-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq5tbwb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq5tbwb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-x-sharp-fill" /></template>

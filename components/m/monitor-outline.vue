<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inh_04poa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inh_04poa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-outline" /></template>

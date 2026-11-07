<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq5k-cbtl.css';
import '../../css/m/m257e8byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5k-cbtl"/><path clip-rule="evenodd" class="m257e8byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-check-bold" /></template>

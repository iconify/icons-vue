<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtem9bcpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtem9bcpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:pencil-to-square" /></template>

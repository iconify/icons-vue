<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs0efx8dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0efx8dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:x" /></template>

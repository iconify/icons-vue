<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb435bcbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb435bcbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:steps" /></template>

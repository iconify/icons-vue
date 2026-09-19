<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsr4lj8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olsr4lj8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:steps-option" /></template>

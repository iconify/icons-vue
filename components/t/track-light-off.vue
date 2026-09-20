<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyptgj2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyptgj2np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:track-light-off" /></template>

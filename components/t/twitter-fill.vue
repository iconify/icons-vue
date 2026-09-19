<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msd0nxxnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msd0nxxnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:twitter-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s730z_fif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="s730z_fif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mickeymouse" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bajwrbb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bajwrbb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octoprint-light" /></template>

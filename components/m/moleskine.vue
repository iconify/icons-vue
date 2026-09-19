<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo1f16ahm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="yo1f16ahm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moleskine" /></template>

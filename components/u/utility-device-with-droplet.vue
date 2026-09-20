<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb5nd5bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eb5nd5bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-device-with-droplet" /></template>

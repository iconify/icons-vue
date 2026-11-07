<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikgh70cpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ikgh70cpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-leanto-building" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahhe4s6pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahhe4s6pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yaml-alt1" /></template>

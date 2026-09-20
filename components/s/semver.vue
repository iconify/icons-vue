<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs2du9u9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs2du9u9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:semver" /></template>

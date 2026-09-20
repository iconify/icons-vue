<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gceupib8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gceupib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pypi" /></template>

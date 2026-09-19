<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psz2ifbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="psz2ifbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:steam" /></template>

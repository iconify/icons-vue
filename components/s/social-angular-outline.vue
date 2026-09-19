<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db5sjti-j.css';
import '../../css/m/mc7-3mbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="db5sjti-j"/><path class="mc7-3mbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-angular-outline" /></template>

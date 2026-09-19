<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwa_iep3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwa_iep3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:milestone-filled" /></template>

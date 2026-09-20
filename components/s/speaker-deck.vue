<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_smkbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs_smkbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:speaker-deck" /></template>

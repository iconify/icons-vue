<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3z_smx1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3z_smx1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vlc-logo" /></template>

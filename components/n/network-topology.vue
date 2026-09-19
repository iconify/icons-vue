<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jily80biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jily80biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:network-topology" /></template>

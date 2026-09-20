<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nggwpp-aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nggwpp-aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-completed" /></template>

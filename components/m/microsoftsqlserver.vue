<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjwc3fslb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjwc3fslb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftsqlserver" /></template>

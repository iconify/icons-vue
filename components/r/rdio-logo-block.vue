<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4q_z4btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4q_z4btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:rdio-logo-block" /></template>

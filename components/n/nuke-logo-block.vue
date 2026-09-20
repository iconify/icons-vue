<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soqjl9b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="soqjl9b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:nuke-logo-block" /></template>

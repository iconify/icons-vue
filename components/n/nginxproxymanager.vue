<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rswbe2bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rswbe2bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nginxproxymanager" /></template>

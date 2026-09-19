<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azq7smbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azq7smbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:scale-filled" /></template>

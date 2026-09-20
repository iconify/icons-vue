<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi-ddebor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi-ddebor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:smbr" /></template>

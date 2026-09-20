<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxbu_zb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxbu_zb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-edit-filled" /></template>

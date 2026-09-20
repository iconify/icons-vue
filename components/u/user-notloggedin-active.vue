<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-0tgb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id-0tgb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:user-notloggedin-active" /></template>

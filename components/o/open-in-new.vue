<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-mhk6xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da-mhk6xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:open-in-new" /></template>

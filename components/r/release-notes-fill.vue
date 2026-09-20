<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs_gzj8dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs_gzj8dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:release-notes-fill" /></template>

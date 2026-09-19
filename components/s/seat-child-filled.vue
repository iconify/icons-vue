<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj0feoo2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj0feoo2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:seat-child-filled" /></template>

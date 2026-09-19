<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkqs-fbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkqs-fbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:note-edit" /></template>

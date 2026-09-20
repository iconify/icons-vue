<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe20_kbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe20_kbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sqlite" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mij9qtw9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mij9qtw9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-veneer-filled" /></template>

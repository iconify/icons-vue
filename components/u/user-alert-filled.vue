<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnhup6rke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnhup6rke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-alert-filled" /></template>

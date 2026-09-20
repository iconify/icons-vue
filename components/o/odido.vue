<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oexk_eb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oexk_eb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:odido" /></template>

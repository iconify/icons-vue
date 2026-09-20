<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkdgngpbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkdgngpbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-waves-solid" /></template>

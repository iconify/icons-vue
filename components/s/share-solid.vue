<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syqrlobng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syqrlobng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:share-solid" /></template>

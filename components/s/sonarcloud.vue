<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afpao8bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afpao8bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sonarcloud" /></template>

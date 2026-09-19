<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwetpntdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwetpntdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:trash" /></template>

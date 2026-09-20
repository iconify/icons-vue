<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahf0zc3zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahf0zc3zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:packagist" /></template>

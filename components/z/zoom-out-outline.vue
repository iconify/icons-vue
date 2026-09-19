<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro8eodbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro8eodbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:zoom-out-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdbs6tbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbs6tbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-running-solid" /></template>

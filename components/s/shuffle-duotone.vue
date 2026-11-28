<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndp62j9zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndp62j9zc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shuffle-duotone" /></template>

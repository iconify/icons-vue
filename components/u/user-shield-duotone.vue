<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esg-30b0c.css';
import '../../css/e/e6yhmq1dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esg-30b0c"/><path class="e6yhmq1dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-shield-duotone" /></template>

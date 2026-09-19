<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s71_e0bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":624,"height":737};
const content = `<path class="s71_e0bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:save" /></template>

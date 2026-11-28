<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok2z6czne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok2z6czne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:unlock-x" /></template>

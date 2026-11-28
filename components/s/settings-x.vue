<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_72eb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_72eb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:settings-x" /></template>

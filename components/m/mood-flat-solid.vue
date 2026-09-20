<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxxm79pjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xxxm79pjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-flat-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe7lczb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe7lczb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-question" /></template>

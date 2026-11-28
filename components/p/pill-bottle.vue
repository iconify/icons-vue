<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms8a113pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms8a113pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pill-bottle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be5srab6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be5srab6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:notes" /></template>

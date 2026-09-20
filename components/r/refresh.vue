<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzyk9jbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzyk9jbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:refresh" /></template>

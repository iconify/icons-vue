<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8w19bbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8w19bbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-permanent-outdoor-light" /></template>

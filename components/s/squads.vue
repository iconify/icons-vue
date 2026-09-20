<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edavw4bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edavw4bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:squads" /></template>

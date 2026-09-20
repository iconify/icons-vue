<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygki8j0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygki8j0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sunset-solid" /></template>

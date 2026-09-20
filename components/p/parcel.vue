<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfk5gh6or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfk5gh6or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:parcel" /></template>

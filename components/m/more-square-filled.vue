<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn3mazb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn3mazb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-square-filled" /></template>

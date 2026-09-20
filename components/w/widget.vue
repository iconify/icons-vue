<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mld7573nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mld7573nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget" /></template>

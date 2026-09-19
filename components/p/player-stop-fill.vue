<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itk9nzlcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itk9nzlcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-stop-fill" /></template>

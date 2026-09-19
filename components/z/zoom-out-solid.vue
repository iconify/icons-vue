<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv3verbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mv3verbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:zoom-out-solid" /></template>

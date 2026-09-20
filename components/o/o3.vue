<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufzzzsbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufzzzsbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:o3" /></template>

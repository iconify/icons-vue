<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afh00gbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afh00gbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:polygon-zkevm" /></template>

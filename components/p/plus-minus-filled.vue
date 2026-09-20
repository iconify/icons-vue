<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfcrs0smz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfcrs0smz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus-minus-filled" /></template>

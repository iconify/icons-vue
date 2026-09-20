<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr3hhsljw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tr3hhsljw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:run3" /></template>

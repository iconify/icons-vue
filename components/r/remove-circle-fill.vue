<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj5i637zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj5i637zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-circle-fill" /></template>

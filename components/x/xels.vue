<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk7r16b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk7r16b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xels" /></template>

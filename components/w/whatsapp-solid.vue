<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8js7pbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8js7pbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:whatsapp-solid" /></template>

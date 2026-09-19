<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_g8w7ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="fk_g8w7ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:router" /></template>

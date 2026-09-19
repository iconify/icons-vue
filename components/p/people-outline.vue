<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d732303fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d732303fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:people-outline" /></template>

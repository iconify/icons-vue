<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywm9fhb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywm9fhb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-5-line" /></template>

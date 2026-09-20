<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktdokp0kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdokp0kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-remove-filled" /></template>

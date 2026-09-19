<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymluktg6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymluktg6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-multiple-02" /></template>

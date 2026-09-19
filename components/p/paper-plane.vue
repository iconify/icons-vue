<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxngdvbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xxngdvbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:paper-plane" /></template>

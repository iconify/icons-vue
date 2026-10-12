<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8qmuvb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x8qmuvb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:unlocked-fill-20" /></template>

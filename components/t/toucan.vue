<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe48pf9zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe48pf9zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:toucan" /></template>

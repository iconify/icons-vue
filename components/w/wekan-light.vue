<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwh_-fbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwh_-fbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wekan-light" /></template>

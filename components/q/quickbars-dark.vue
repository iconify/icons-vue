<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ftkyb5l.css';
import '../../css/y/yerqhxb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_ftkyb5l"/><path class="yerqhxb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickbars-dark" /></template>

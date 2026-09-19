<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttn-_-n5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1932,"height":701};
const content = `<path class="ttn-_-n5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sqale" /></template>

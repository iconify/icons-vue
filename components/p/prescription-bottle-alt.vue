<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7yu7jbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f7yu7jbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:prescription-bottle-alt" /></template>

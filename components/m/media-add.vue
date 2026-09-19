<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ifm72mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p_ifm72mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:media-add" /></template>

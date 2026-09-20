<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoplcy1aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoplcy1aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tripadvisor" /></template>

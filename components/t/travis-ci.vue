<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayt0x815c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayt0x815c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:travis-ci" /></template>

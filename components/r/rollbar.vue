<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dle0albcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dle0albcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rollbar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe2b1e9jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe2b1e9jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:opsgenie" /></template>

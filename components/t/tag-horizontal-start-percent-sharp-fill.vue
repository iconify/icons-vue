<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5h70p1ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5h70p1ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-percent-sharp-fill" /></template>
